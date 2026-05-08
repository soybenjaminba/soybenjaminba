# Documentación del blog soybenjaminba.com

Todo lo que necesitas saber para recuperar, mantener y expandir el blog desde cero.

---

## Stack tecnológico

| Herramienta | Rol | Versión |
|---|---|---|
| **Hugo** | Generador de sitio estático | 0.147.0 (extended) |
| **Blowfish** | Tema visual | última versión (main) |
| **GitHub** | Repositorio del código | github.com/soybenjaminba/soybenjaminba |
| **GitHub Pages** | Hosting gratuito | — |
| **GitHub Actions** | Deploy automático al hacer push | — |
| **Google Analytics** | Estadísticas de visitas | G-F3FXMYS08Z |
| **Dominio** | soybenjaminba.com | Registrado externamente |

**Cómo funciona el flujo completo:**
Escribes un post → haces `git push origin main` → GitHub Actions construye el sitio automáticamente → el sitio se publica en soybenjaminba.com en ~2 minutos.

---

## Recuperar el blog en una computadora nueva

```bash
# 1. Clonar el repositorio con el tema incluido
git clone --recurse-submodules https://github.com/soybenjaminba/soybenjaminba
cd soybenjaminba

# 2. Instalar Hugo (Mac con Homebrew)
brew install hugo

# 3. Verificar que todo funciona localmente
hugo server

# Abre http://localhost:1313 en el navegador
```

> El flag `--recurse-submodules` es importante: descarga también el tema Blowfish, que está enlazado como submódulo en `themes/blowfish/`.

---

## Estructura de carpetas

```
soybenjaminba/
├── config/_default/          # Toda la configuración del sitio
│   ├── hugo.toml             # Config principal (baseURL, tema, Analytics)
│   ├── languages.es.toml     # Nombre del autor, bio, foto, redes sociales
│   ├── menus.es.toml         # Menú de navegación (Blog, Acerca de, Etiquetas)
│   ├── params.toml           # Apariencia (colores, dark mode, layout)
│   └── markup.toml           # Permite HTML/SVG inline en los posts
│
├── content/
│   ├── acerca-de/index.md    # Página "Acerca de" con el CV
│   └── posts/
│       ├── nombre-post.md              # Post sin imágenes (archivo único)
│       └── nombre-post-con-imagenes/   # Post con imágenes (carpeta = page bundle)
│           ├── index.md
│           └── imagen.png
│
├── layouts/                  # Overrides del tema (correcciones de compatibilidad)
│   ├── _default/
│   │   ├── baseof.html
│   │   └── single.html
│   └── partials/
│       ├── head.html
│       ├── schema.html
│       ├── sharing-links.html
│       ├── contributors.html
│       ├── sponsors.html
│       └── vendor.html
│
├── assets/img/profile.jpg    # Foto de perfil
├── static/CNAME              # Dominio personalizado (soybenjaminba.com)
├── themes/blowfish/          # Tema (submódulo de git, no editar)
└── .github/workflows/        # Pipeline de deploy automático
    └── hugo.yml
```

---

## Archivos de configuración clave

### `config/_default/hugo.toml`
Config general del sitio. Si cambias el dominio, actualiza `baseURL`.

```toml
theme = "blowfish"
baseURL = "https://soybenjaminba.com/"
defaultContentLanguage = "es"

[services]
  [services.googleAnalytics]
    ID = "G-F3FXMYS08Z"
```

### `config/_default/languages.es.toml`
Nombre del autor, foto de perfil, bio y links de redes sociales.

```toml
title = "Benjamín Barragán Abad"

[params.author]
  name = "Benjamín Barragán Abad"
  image = "img/profile.jpg"       # Ruta relativa a assets/
  headline = "Economista · Finanzas · Inversiones"
  bio = "Escribo sobre economía..."
  links = [
    { linkedin = "https://linkedin.com/in/soybenjaminba" },
    { github = "https://github.com/soybenjaminba" },
    { email = "mailto:soybenjaminba@gmail.com" },
  ]
```

### `config/_default/params.toml`
Controla la apariencia visual. Los valores más importantes:

```toml
colorScheme = "slate"        # Paleta de colores (slate, ocean, fire, etc.)
defaultAppearance = "dark"   # dark o light
autoSwitchAppearance = true  # Detecta preferencia del sistema operativo

[homepage]
  layout = "profile"         # Muestra foto y bio en la página principal
```

### `config/_default/markup.toml`
Permite usar HTML y SVG directamente dentro del markdown de los posts. Necesario para las gráficas SVG inline.

```toml
[goldmark.renderer]
  unsafe = true
```

---

## Cómo crear un nuevo post

### Post sin imágenes (archivo único)

```bash
# Crear el archivo
touch content/posts/nombre-del-post.md
```

Estructura del archivo:

```markdown
+++
title = "Título del post"
date = "2026-05-08"
description = "Descripción breve que aparece en el listado."
tags = ["economía", "finanzas"]
showTableOfContents = true
+++

Contenido del post en markdown...
```

### Post con imágenes (page bundle = carpeta)

```bash
# Crear la carpeta y el archivo principal
mkdir content/posts/nombre-del-post
# Copiar las imágenes a esa misma carpeta
cp mis-imagenes/*.png content/posts/nombre-del-post/
```

El archivo principal debe llamarse `index.md` y las imágenes se referencian por nombre simple:

```markdown
![Descripción](nombre-imagen.png)
```

Para centrar una imagen:

```html
<div style="text-align:center; margin:28px 0;">
<img src="nombre-imagen.png" alt="Descripción" style="max-width:100%; border-radius:6px;">
</div>
```

### Gráficas SVG inline

Para incrustar una gráfica directamente en el post (sin imagen externa), usa un bloque `<div>` con SVG. El `markup.toml` tiene `unsafe = true` activado para que funcione.

```html
<div style="margin:28px 0;">
  <svg viewBox="0 0 720 380" xmlns="http://www.w3.org/2000/svg"
       style="max-width:100%;height:auto;background:#ffffff;border-radius:8px;padding:8px;">
    <!-- contenido SVG -->
  </svg>
</div>
```

> Importante: siempre agrega `background:#ffffff` al SVG para que se vea bien en modo oscuro.

---

## Deploy: publicar cambios

```bash
# Agregar los archivos nuevos o modificados
git add .

# Crear el commit
git commit -m "Descripción del cambio"

# Publicar — GitHub Actions hace el build y deploy automáticamente
git push origin main
```

El sitio se actualiza en aproximadamente 2 minutos. Puedes ver el estado del deploy en:
`https://github.com/soybenjaminba/soybenjaminba/actions`

---

## Por qué existen los overrides en `layouts/`

Hugo 0.147.0 introdujo cambios que rompieron la compatibilidad con el tema Blowfish. En lugar de modificar los archivos del tema (que se sobreescribirían al actualizar), se crearon overrides en `layouts/` que Hugo prioriza automáticamente.

| Archivo override | Problema que resuelve |
|---|---|
| `layouts/_default/baseof.html` | `.Language.Locale` → `.Language.Lang` |
| `layouts/partials/head.html` | `.Site.Language.Locale` → `.Site.Language.Lang` |
| `layouts/partials/schema.html` | `.Site.Language.Locale` → `.Site.Language.Lang` |
| `layouts/_default/single.html` | `hugo.Data.authors` → `dict` |
| `layouts/partials/sharing-links.html` | `hugo.Data.sharing` → `site.Data.sharing` |
| `layouts/partials/contributors.html` | `hugo.Data.contributors` → `site.Data.contributors` |
| `layouts/partials/sponsors.html` | `hugo.Data.sponsors` → `site.Data.sponsors` |
| `layouts/partials/vendor.html` | `hugo.Data.repoColors` → `site.Data.repoColors` |

> Si en el futuro actualizas Blowfish y el sitio deja de construirse, revisa primero estos archivos.

---

## Google Analytics

ID de medición: `G-F3FXMYS08Z`

Las estadísticas se ven en [analytics.google.com](https://analytics.google.com). Para ver visitas en tiempo real: **Informes → Tiempo real**.

La configuración está en `config/_default/hugo.toml` bajo `[services.googleAnalytics]`.

---

## Dominio personalizado

El archivo `static/CNAME` contiene `soybenjaminba.com`. Este archivo le indica a GitHub Pages cuál es el dominio personalizado. No borrar.

La configuración DNS (registros A o CNAME apuntando a GitHub) está en el panel de tu registrador de dominios, no en este repositorio.

---

## Actualizar el tema Blowfish

```bash
# Actualizar el submódulo a la versión más reciente
git submodule update --remote themes/blowfish

# Si el build falla después de actualizar, revisar los overrides en layouts/
# (ver sección anterior sobre compatibilidad)
```

---

## Posts publicados

| Post | Archivo | Tipo |
|---|---|---|
| El Apagón Silencioso (vitaminas D y B12) | `content/posts/consecuencias-deficiencia-vitamina-d-b12.md` | Archivo único |
| La trampa del colateral | `content/posts/trampa-del-colateral.md` | Archivo único con SVGs inline |
| Santiago Ixmatlahuacan: diagnóstico municipal | `content/posts/ixmatlahuacan-radiografia/index.md` | Page bundle con 7 imágenes PNG |

---

*Última actualización: mayo 2026*
