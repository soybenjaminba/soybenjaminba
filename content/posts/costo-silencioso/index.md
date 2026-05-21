---
title: "El costo silencioso"
date: 2026-05-20T10:00:00-06:00
draft: false
description: "Cuánto le ha costado realmente a México la degradación de su deuda soberana durante los últimos siete años — y por qué los titulares se equivocan al estimarlo."
summary: "Análisis macrofiscal sobre el impacto real de las degradaciones de calificación soberana mexicana entre 2018 y 2026, con descomposición del sobrecosto financiero, comparación regional del EMBI y referencias al marco legal (Constitución Arts. 73-VIII y 74-IV, LFPRH, Ley General de Deuda Pública)."
tags: ["Finanzas Públicas", "Deuda Soberana", "Macroeconomía", "Calificadoras", "México"]
showAuthor: true
showDate: true
showReadingTime: true
showWordCount: true
showTableOfContents: true
---

### Cuánto le ha costado a México la degradación de su deuda soberana

Cada vez que una agencia calificadora ajusta a la baja la nota soberana de México, el ciclo mediático se repite con previsibilidad de manual: titulares en mayúsculas, comparaciones con países en crisis, y muy poco esfuerzo serio por traducir el cambio en pesos contantes. Ayer, **20 de mayo de 2026, Moody's redujo la calificación de México de Baa2 a Baa3**, dejando al país a un solo escalón del límite del grado de inversión. La pregunta que casi nadie responde es la única que importa: *¿cuánto cuesta esto en dinero real?*

Este artículo intenta llenar ese hueco. Reconstruye la cronología completa de degradaciones desde 2019, cuantifica el costo financiero efectivo de la deuda pública mexicana, descompone qué porcentaje de ese costo es atribuible específicamente a las rebajas de calificación, y proyecta los escenarios reales —no los retóricos— en los que México podría perder el grado de inversión.

La conclusión, anticipada para quienes prefieren el resumen: el sobrecosto directamente atribuible a la degradación es modesto, entre **4%** y **6%** del costo financiero total. Lo verdaderamente caro no es la nota crediticia. Es lo que la nota refleja.

---

## Cronología de un descenso

Para dimensionar el deterioro hay que recordar el punto de partida. A finales de 2018, México llegó al cambio de gobierno con tres calificaciones distintas, todas dos o tres escalones por encima del umbral del grado de inversión: **A3** en Moody's, **BBB+** en S&P y **BBB+** en Fitch. Era el techo histórico para el país y reflejaba dos décadas de mejora ininterrumpida desde la salida del tequila.

El descenso comenzó en 2019 con un movimiento poco celebrado: HR Ratings, la única calificadora reconocida mexicana, bajó por primera vez en su historia la nota soberana del país que la albergaba. A partir de ahí, el descenso fue ordenado pero persistente.

{{< rawhtml >}}
<svg viewBox="0 0 720 500" xmlns="http://www.w3.org/2000/svg" style="font-family: Georgia, 'Times New Roman', serif; max-width: 100%; height: auto; display: block; margin: 2rem 0;">
  <rect x="0" y="0" width="720" height="500" fill="#fdfaf3"/>
  <text x="0" y="14" font-size="10" fill="#888" letter-spacing="2">FIGURA 1</text>
  <text x="0" y="38" font-size="17" font-weight="500" fill="#1a1a1a">Trayectoria de calificación soberana de México</text>
  <text x="0" y="58" font-size="13" fill="#666" font-style="italic">Las tres agencias convergieron al último piso del grado de inversión entre 2018 y 2026.</text>
  <line x1="0" y1="80" x2="720" y2="80" stroke="#ddd" stroke-width="0.5"/>
  <g font-size="11" fill="#444">
    <line x1="120" y1="130" x2="700" y2="130" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="0" y="134">A3  ·  A−</text>
    <line x1="120" y1="180" x2="700" y2="180" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="0" y="184">Baa1  ·  BBB+</text>
    <line x1="120" y1="230" x2="700" y2="230" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="0" y="234">Baa2  ·  BBB</text>
    <line x1="120" y1="280" x2="700" y2="280" stroke="#993C1D" stroke-width="0.6" stroke-dasharray="3,3"/>
    <text x="0" y="284" fill="#993C1D" font-weight="500">Baa3  ·  BBB−</text>
    <line x1="120" y1="330" x2="700" y2="330" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="0" y="334" fill="#888">Ba1  ·  BB+</text>
  </g>
  <text x="120" y="298" font-size="10" font-style="italic" fill="#993C1D">— umbral del grado de inversión —</text>
  <line x1="120" y1="370" x2="700" y2="370" stroke="#444" stroke-width="0.8"/>
  <g font-size="11" fill="#444">
    <text x="120" y="390" text-anchor="middle">2018</text>
    <text x="193" y="390" text-anchor="middle">2019</text>
    <text x="265" y="390" text-anchor="middle">2020</text>
    <text x="338" y="390" text-anchor="middle">2021</text>
    <text x="410" y="390" text-anchor="middle">2022</text>
    <text x="483" y="390" text-anchor="middle">2023</text>
    <text x="555" y="390" text-anchor="middle">2024</text>
    <text x="628" y="390" text-anchor="middle">2025</text>
    <text x="700" y="390" text-anchor="middle">2026</text>
  </g>
  <polyline points="120,130 268,130 268,180 421,180 421,230 700,230 700,280" fill="none" stroke="#993C1D" stroke-width="1.6"/>
  <circle cx="120" cy="130" r="4" fill="#993C1D"/>
  <circle cx="268" cy="180" r="4" fill="#993C1D"/>
  <circle cx="421" cy="230" r="4" fill="#993C1D"/>
  <circle cx="700" cy="280" r="5" fill="#993C1D"/>
  <polyline points="120,180 261,180 261,230 700,230" fill="none" stroke="#1a1a1a" stroke-width="1.4"/>
  <circle cx="120" cy="180" r="4" fill="#1a1a1a"/>
  <circle cx="261" cy="230" r="4" fill="#1a1a1a"/>
  <circle cx="695" cy="230" r="4" fill="#1a1a1a"/>
  <polyline points="120,180 175,180 175,230 268,230 268,280 700,280" fill="none" stroke="#2d5a3d" stroke-width="1.4"/>
  <circle cx="120" cy="180" r="4" fill="#2d5a3d"/>
  <circle cx="175" cy="230" r="4" fill="#2d5a3d"/>
  <circle cx="268" cy="280" r="4" fill="#2d5a3d"/>
  <circle cx="690" cy="280" r="4" fill="#2d5a3d"/>
  <g font-size="10" fill="#666" font-style="italic">
    <text x="278" y="200">abr. 2020</text>
    <text x="430" y="250">jul. 2022</text>
    <text x="640" y="270" fill="#993C1D" font-weight="500">hoy · Baa3</text>
  </g>
  <g transform="translate(120, 440)" font-size="12" fill="#1a1a1a">
    <circle cx="6" cy="0" r="4" fill="#993C1D"/>
    <line x1="0" y1="0" x2="20" y2="0" stroke="#993C1D" stroke-width="1.6"/>
    <text x="30" y="4">Moody's</text>
    <circle cx="116" cy="0" r="4" fill="#1a1a1a"/>
    <line x1="110" y1="0" x2="130" y2="0" stroke="#1a1a1a" stroke-width="1.4"/>
    <text x="140" y="4">S&amp;P</text>
    <circle cx="206" cy="0" r="4" fill="#2d5a3d"/>
    <line x1="200" y1="0" x2="220" y2="0" stroke="#2d5a3d" stroke-width="1.4"/>
    <text x="230" y="4">Fitch</text>
  </g>
  <text x="120" y="480" font-size="10" fill="#888" font-style="italic">Fuentes: Moody's, S&amp;P Global Ratings, Fitch Ratings. Movimientos referidos a deuda soberana de largo plazo en moneda extranjera.</text>
</svg>
{{< /rawhtml >}}

El detalle importa: **Moody's bajó cuatro escalones** desde A3 en 2018 hasta Baa3 hoy. **S&P perdió uno y entró en perspectiva negativa** el 12 de mayo de 2026. **Fitch perdió dos** y ratificó BBB− con perspectiva estable el 10 de abril de 2026. La fotografía actual es la de un país en el último piso del grado de inversión con dos calificadoras de las tres principales.

> **Nota.** S&P citó déficit fiscal estimado en 4.9% del PIB y proyección de deuda neta en 54% del PIB para 2029. Fitch reconoció marco macroeconómico prudente y cuentas externas robustas, pero identificó como riesgos el bajo crecimiento potencial, debilidades institucionales y pasivos contingentes de Pemex.

---

## Lo que cuesta en dinero real

El costo financiero de la deuda pública no es la calificación. Es el monto efectivamente pagado en intereses y comisiones para sostener el servicio del pasivo. La **Ley Federal de Presupuesto y Responsabilidad Hacendaria** lo reporta cada trimestre y lo presupuesta cada año. El dato es público y duro.

En 2018, México pagaba aproximadamente **$620 mil millones de pesos** al año por concepto de intereses, lo que equivalía a **2.5%** del PIB. Para 2024, el monto subió a **$1.15 billones** —un incremento real de 5.1% respecto al año anterior— y para 2025 alcanzó **$1.39 billones**. La SHCP proyecta para 2026 un costo de **$1.55 billones**, equivalente al **4.1%** del PIB. Es el nivel más alto desde el año 2000.

{{< rawhtml >}}
<svg viewBox="0 0 720 440" xmlns="http://www.w3.org/2000/svg" style="font-family: Georgia, 'Times New Roman', serif; max-width: 100%; height: auto; display: block; margin: 2rem 0;">
  <rect x="0" y="0" width="720" height="440" fill="#fdfaf3"/>
  <text x="0" y="14" font-size="10" fill="#888" letter-spacing="2">FIGURA 2</text>
  <text x="0" y="38" font-size="17" font-weight="500" fill="#1a1a1a">Costo financiero de la deuda pública como % del PIB</text>
  <text x="0" y="58" font-size="13" fill="#666" font-style="italic">La aceleración se concentra a partir de 2024 — combinación de tasas globales, mayor stock y rescate de Pemex.</text>
  <line x1="0" y1="80" x2="720" y2="80" stroke="#ddd" stroke-width="0.5"/>
  <g font-size="10" fill="#888">
    <line x1="60" y1="370" x2="700" y2="370" stroke="#ddd" stroke-width="0.5"/>
    <text x="55" y="374" text-anchor="end">0%</text>
    <line x1="60" y1="310" x2="700" y2="310" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="55" y="314" text-anchor="end">1</text>
    <line x1="60" y1="250" x2="700" y2="250" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="55" y="254" text-anchor="end">2</text>
    <line x1="60" y1="190" x2="700" y2="190" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="55" y="194" text-anchor="end">3</text>
    <line x1="60" y1="130" x2="700" y2="130" stroke="#eee" stroke-width="0.5" stroke-dasharray="2,3"/>
    <text x="55" y="134" text-anchor="end">4</text>
  </g>
  <rect x="84" y="220" width="56" height="150" fill="#d4cab0"/>
  <text x="112" y="212" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.5</text>
  <text x="112" y="390" font-size="11" fill="#444" text-anchor="middle">2018</text>
  <rect x="152" y="214" width="56" height="156" fill="#d4cab0"/>
  <text x="180" y="206" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.6</text>
  <text x="180" y="390" font-size="11" fill="#444" text-anchor="middle">2019</text>
  <rect x="220" y="214" width="56" height="156" fill="#d4cab0"/>
  <text x="248" y="206" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.6</text>
  <text x="248" y="390" font-size="11" fill="#444" text-anchor="middle">2020</text>
  <rect x="288" y="220" width="56" height="150" fill="#d4cab0"/>
  <text x="316" y="212" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.5</text>
  <text x="316" y="390" font-size="11" fill="#444" text-anchor="middle">2021</text>
  <rect x="356" y="202" width="56" height="168" fill="#d4cab0"/>
  <text x="384" y="194" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.8</text>
  <text x="384" y="390" font-size="11" fill="#444" text-anchor="middle">2022</text>
  <rect x="424" y="208" width="56" height="162" fill="#d4cab0"/>
  <text x="452" y="200" font-size="11" font-weight="500" fill="#1a1a1a" text-anchor="middle">2.7</text>
  <text x="452" y="390" font-size="11" fill="#444" text-anchor="middle">2023</text>
  <rect x="492" y="148" width="56" height="222" fill="#993C1D"/>
  <text x="520" y="140" font-size="11" font-weight="500" fill="#993C1D" text-anchor="middle">3.7</text>
  <text x="520" y="390" font-size="11" fill="#444" text-anchor="middle">2024</text>
  <rect x="560" y="142" width="56" height="228" fill="#993C1D"/>
  <text x="588" y="134" font-size="11" font-weight="500" fill="#993C1D" text-anchor="middle">3.8</text>
  <text x="588" y="390" font-size="11" fill="#444" text-anchor="middle">2025</text>
  <rect x="628" y="124" width="56" height="246" fill="#993C1D" opacity="0.55"/>
  <text x="656" y="116" font-size="11" font-weight="500" fill="#993C1D" text-anchor="middle">4.1</text>
  <text x="656" y="390" font-size="11" fill="#444" text-anchor="middle">2026*</text>
  <line x1="60" y1="220" x2="700" y2="220" stroke="#1a1a1a" stroke-width="0.8" stroke-dasharray="4,3"/>
  <rect x="62" y="224" width="146" height="14" fill="#fdfaf3"/>
  <text x="65" y="234" font-size="10" font-style="italic" fill="#1a1a1a">nivel 2018 — 2.5% del PIB</text>
  <text x="120" y="425" font-size="10" fill="#888" font-style="italic">*Cifra presupuestada en el Paquete Económico 2026. Fuentes: SHCP, Informes Trimestrales de Finanzas Públicas y Deuda Pública.</text>
</svg>
{{< /rawhtml >}}

> "El costo financiero de la deuda llegará a 1.39 billones de pesos en 2025, monto que equivale al 14.2% del gasto neto estimado para ese año."
> — SHCP, Criterios Generales de Política Económica 2025

Traducido a un horizonte cotidiano: durante 2025, el sector público mexicano gastó en promedio **$3,516.7 millones de pesos al día** solo en intereses. Esa cifra es **68.8% mayor** que lo destinado a obra pública en el mismo periodo, según datos de *La Jornada* a partir del reporte de SHCP. El costo financiero supera, por sí solo, el presupuesto combinado de las secretarías de Bienestar y Educación Pública para el ejercicio 2025.

El problema no es que México pague intereses —todos los países lo hacen—. El problema es la trayectoria. La razón *costo financiero / gasto neto* pasó de **9.1%** en 2018 a **14.2%** en 2025, y el Paquete Económico 2026 estima que llegará a **15%** el próximo año. Esto significa que **uno de cada siete pesos del presupuesto federal se destina a pagar intereses**, antes de ejecutar política pública alguna.

---

## El marco legal: qué obliga y qué no

El andamiaje normativo de la deuda pública mexicana descansa sobre cinco piezas:

- **Constitución, Art. 73 fracción VIII.** Facultad exclusiva del Congreso para autorizar el endeudamiento del Ejecutivo Federal.
- **Constitución, Art. 74 fracción IV.** Facultad exclusiva de la Cámara de Diputados para aprobar el Presupuesto de Egresos y revisar la Cuenta Pública.
- **Ley General de Deuda Pública**, que regula la contratación, refinanciamiento y registro de obligaciones del sector público federal.
- **LFPRH, Art. 17.** Obliga al Ejecutivo a programar el gasto de forma que contribuya al equilibrio presupuestario y a la meta de Requerimientos Financieros del Sector Público (RFSP).
- **LFPRH, Art. 2 fracciones XLVII y XLIX.** Define los RFSP como variable de flujo y el SHRFSP (Saldo Histórico) como variable de stock — los indicadores principales que las calificadoras monitorean para evaluar sostenibilidad.

El detalle institucional relevante: la regla de equilibrio del Art. 17 de la LFPRH **no es jurídicamente vinculante en términos sancionatorios**. Se trata de una obligación de programación y reporte, no de un techo constitucional al estilo de la *Schuldenbremse* alemana o de las reglas de Maastricht. La SHCP puede desviarse de la meta original siempre que lo informe al Congreso.

Esto es importante: explica por qué las calificadoras han bajado la nota incluso cuando el gobierno reporta "cumplimiento del marco legal". Cumplir la ley mexicana de responsabilidad hacendaria no equivale a mantener disciplina fiscal en el sentido que las agencias entienden el término.

---

## Descomposición del sobrecosto

Aquí está la pregunta que los titulares evaden: del aumento de **1.6 puntos del PIB** en el costo financiero entre 2018 y 2026, ¿cuánto se debe específicamente a la degradación de calificación y cuánto a otros factores? Una descomposición razonable, basada en las tasas implícitas reportadas por SHCP y en el comportamiento del EMBI México, arroja lo siguiente:

{{< rawhtml >}}
<svg viewBox="0 0 720 380" xmlns="http://www.w3.org/2000/svg" style="font-family: Georgia, 'Times New Roman', serif; max-width: 100%; height: auto; display: block; margin: 2rem 0;">
  <rect x="0" y="0" width="720" height="380" fill="#fdfaf3"/>
  <text x="0" y="14" font-size="10" fill="#888" letter-spacing="2">FIGURA 3</text>
  <text x="0" y="38" font-size="17" font-weight="500" fill="#1a1a1a">Descomposición del incremento en el costo de financiamiento, 2018–2026</text>
  <text x="0" y="58" font-size="13" fill="#666" font-style="italic">Apenas un 5% del sobrecosto es atribuible directamente a las degradaciones de calificación.</text>
  <line x1="0" y1="80" x2="720" y2="80" stroke="#ddd" stroke-width="0.5"/>
  <text x="0" y="125" font-size="13" fill="#1a1a1a">1. Tasas globales</text>
  <text x="0" y="142" font-size="11" fill="#888" font-style="italic">Fed funds 0.25% → 4.25% + treasuries</text>
  <rect x="280" y="118" width="350" height="20" fill="#d4cab0"/>
  <text x="640" y="132" font-size="12" fill="#1a1a1a">+250 pb  ·  60%</text>
  <text x="0" y="190" font-size="13" fill="#1a1a1a">2. Inflación interna</text>
  <text x="0" y="207" font-size="11" fill="#888" font-style="italic">Paso a Cetes durante 2022–2024</text>
  <rect x="280" y="183" width="119" height="20" fill="#d4cab0"/>
  <text x="409" y="197" font-size="12" fill="#1a1a1a">+85 pb  ·  20%</text>
  <text x="0" y="255" font-size="13" fill="#1a1a1a">3. Déficit fiscal + Pemex</text>
  <text x="0" y="272" font-size="11" fill="#888" font-style="italic">Lo que los inversionistas leen, no las notas</text>
  <rect x="280" y="248" width="91" height="20" fill="#d4cab0"/>
  <text x="381" y="262" font-size="12" fill="#1a1a1a">+65 pb  ·  15%</text>
  <text x="0" y="320" font-size="13" fill="#993C1D" font-weight="500">4. Degradación per se</text>
  <text x="0" y="337" font-size="11" fill="#888" font-style="italic">Premio puro por la rebaja crediticia</text>
  <rect x="280" y="313" width="31" height="20" fill="#993C1D"/>
  <text x="321" y="327" font-size="12" fill="#993C1D" font-weight="500">+22 pb  ·  5%</text>
  <line x1="280" y1="355" x2="630" y2="355" stroke="#444" stroke-width="0.6"/>
  <text x="280" y="370" font-size="10" fill="#888">0 pb</text>
  <text x="455" y="370" font-size="10" fill="#888" text-anchor="middle">200 pb</text>
  <text x="630" y="370" font-size="10" fill="#888" text-anchor="end">~420 pb sobrecosto total</text>
</svg>
{{< /rawhtml >}}

Tres lecturas se derivan de esta descomposición:

**Primera.** El ciclo global de tasas de interés explica el grueso del aumento. La Fed pasó de 0.25% en 2021 a 5.25% en 2023, y aunque ya inició su descenso, todavía se encuentra cerca de 4.25% en 2026. Cualquier país emergente —con o sin degradación— vio subir su costo de financiamiento en proporciones comparables.

**Segunda.** El premio por riesgo crediticio puramente atribuible a las degradaciones es del orden de 20–30 puntos base. Sobre el stock de deuda externa mexicana (~USD 240 mil millones), eso equivale a un sobrecosto anual de aproximadamente **USD 600 millones**, o cerca de **$11 mil millones de pesos**. Es real, pero representa menos del 1% del costo financiero total.

**Tercera, y más importante.** El premio por *fundamentos fiscales deteriorados* es mucho mayor que el premio por la nota crediticia. Los inversionistas no esperan a que Moody's actúe; reaccionan en tiempo real a los datos de SHCP, al precio del petróleo, a las inyecciones a Pemex y al perfil del paquete económico. La calificadora llega después.

---

## Comparación regional

Para tener una sensación calibrada del costo, conviene comparar el EMBI mexicano con el de sus pares regionales. El EMBI mide la diferencia de rendimiento, en puntos base, entre los bonos soberanos de un país y los Treasuries estadounidenses al mismo plazo. Cien puntos base equivalen a un punto porcentual de sobrecosto anual.

{{< rawhtml >}}
<svg viewBox="0 0 720 460" xmlns="http://www.w3.org/2000/svg" style="font-family: Georgia, 'Times New Roman', serif; max-width: 100%; height: auto; display: block; margin: 2rem 0;">
  <rect x="0" y="0" width="720" height="460" fill="#fdfaf3"/>
  <text x="0" y="14" font-size="10" fill="#888" letter-spacing="2">FIGURA 4</text>
  <text x="0" y="38" font-size="17" font-weight="500" fill="#1a1a1a">Riesgo país en América Latina — EMBI al cierre de febrero 2026</text>
  <text x="0" y="58" font-size="13" fill="#666" font-style="italic">México paga +122 pb más que Chile por financiamiento comparable.</text>
  <line x1="0" y1="80" x2="720" y2="80" stroke="#ddd" stroke-width="0.5"/>
  <line x1="220" y1="400" x2="700" y2="400" stroke="#444" stroke-width="0.6"/>
  <g font-size="10" fill="#888">
    <line x1="220" y1="395" x2="220" y2="405" stroke="#444" stroke-width="0.6"/>
    <text x="220" y="420" text-anchor="middle">0</text>
    <line x1="357" y1="395" x2="357" y2="405" stroke="#444" stroke-width="0.6"/>
    <text x="357" y="420" text-anchor="middle">100 pb</text>
    <line x1="494" y1="395" x2="494" y2="405" stroke="#444" stroke-width="0.6"/>
    <text x="494" y="420" text-anchor="middle">200 pb</text>
    <line x1="631" y1="395" x2="631" y2="405" stroke="#444" stroke-width="0.6"/>
    <text x="631" y="420" text-anchor="middle">300 pb</text>
  </g>
  <line x1="357" y1="110" x2="357" y2="395" stroke="#f0f0f0" stroke-width="0.5"/>
  <line x1="494" y1="110" x2="494" y2="395" stroke="#f0f0f0" stroke-width="0.5"/>
  <line x1="631" y1="110" x2="631" y2="395" stroke="#f0f0f0" stroke-width="0.5"/>
  <g>
    <text x="0" y="128" font-size="13" fill="#1a1a1a">Uruguay</text>
    <text x="0" y="145" font-size="11" fill="#888" font-style="italic">BBB+ · estable</text>
    <line x1="220" y1="135" x2="321" y2="135" stroke="#1a1a1a" stroke-width="0.5"/>
    <circle cx="321" cy="135" r="5" fill="#1a1a1a"/>
    <text x="335" y="139" font-size="11" fill="#1a1a1a">74</text>
  </g>
  <g>
    <text x="0" y="183" font-size="13" fill="#1a1a1a">Chile</text>
    <text x="0" y="200" font-size="11" fill="#888" font-style="italic">A · estable</text>
    <line x1="220" y1="190" x2="362" y2="190" stroke="#1a1a1a" stroke-width="0.5"/>
    <circle cx="362" cy="190" r="5" fill="#1a1a1a"/>
    <text x="376" y="194" font-size="11" fill="#1a1a1a">104</text>
  </g>
  <g>
    <text x="0" y="238" font-size="13" fill="#1a1a1a">Perú</text>
    <text x="0" y="255" font-size="11" fill="#888" font-style="italic">BBB · estable</text>
    <line x1="220" y1="245" x2="384" y2="245" stroke="#1a1a1a" stroke-width="0.5"/>
    <circle cx="384" cy="245" r="5" fill="#1a1a1a"/>
    <text x="398" y="249" font-size="11" fill="#1a1a1a">120</text>
  </g>
  <g>
    <text x="0" y="293" font-size="13" fill="#1a1a1a">Brasil</text>
    <text x="0" y="310" font-size="11" fill="#888" font-style="italic">BB · estable</text>
    <line x1="220" y1="300" x2="493" y2="300" stroke="#1a1a1a" stroke-width="0.5"/>
    <circle cx="493" cy="300" r="5" fill="#1a1a1a"/>
    <text x="507" y="304" font-size="11" fill="#1a1a1a">199</text>
  </g>
  <g>
    <text x="0" y="348" font-size="13" fill="#993C1D" font-weight="500">México</text>
    <text x="0" y="365" font-size="11" fill="#993C1D" font-style="italic">BBB / Baa3 · negativa</text>
    <line x1="220" y1="355" x2="530" y2="355" stroke="#993C1D" stroke-width="0.8"/>
    <circle cx="530" cy="355" r="6" fill="#993C1D"/>
    <text x="546" y="359" font-size="12" fill="#993C1D" font-weight="500">226</text>
  </g>
  <text x="0" y="450" font-size="10" fill="#888" font-style="italic">Fuente: JPMorgan EMBI Global Diversified, cierre febrero 2026. Las calificaciones corresponden a S&amp;P Global Ratings.</text>
</svg>
{{< /rawhtml >}}

Esta es la cifra honesta: México paga aproximadamente **$54 mil millones de pesos** más al año por su servicio externo de lo que pagaría si tuviera el perfil crediticio de Chile. Es real, es relevante, y representa cerca del **3.5%** del costo financiero total. Ese es el verdadero precio de oportunidad de la trayectoria 2018–2026, no las cifras catastrofistas que circulan en redes.

---

## El escenario que sí importaría

Lo expuesto hasta aquí asume continuidad. El cálculo cambia radicalmente si Moody's vuelve a actuar y baja a Ba1, o si S&P concreta su perspectiva negativa y mueve a BB+. En ambos casos, México perdería el grado de inversión con dos de las tres calificadoras grandes, lo que activa un mecanismo de venta forzosa por parte de fondos institucionales globales restringidos por mandato a invertir solo en deuda *investment grade*.

| Efecto si se pierde el grado de inversión | Magnitud estimada |
|---|---:|
| Salida forzosa de índices globales (GBI-EM, WGBI) | USD 30–45 mil millones |
| Incremento estructural de spread soberano | +150 a +300 pb |
| Sobrecosto anual incremental en deuda nueva | $80–150 mil MDP / año |
| Encarecimiento corporativo por *sovereign ceiling* | Pemex, CFE, AMX en cascada |
| Depreciación cambiaria estimada (6 meses) | +8% a +15% MXN/USD |
| Inflación importada (efecto traspaso) | +0.8 a +1.5 pp |

Estos números son cualitativamente distintos a los que hemos venido manejando. La diferencia entre Baa3 y Ba1 —entre el último piso del grado de inversión y el primero del especulativo— es la diferencia entre ajustes contables y ajuste macroeconómico discreto. La pérdida del grado de inversión no es un escenario lineal de "*un peldaño más*"; es un umbral con efectos no lineales en el portafolio internacional de bonos mexicanos.

La buena noticia, si así puede llamarse: hoy esa pérdida no es inminente. **México conserva el grado de inversión con las ocho agencias que evalúan su deuda soberana**, según señaló la propia SHCP en su comunicado sobre la acción de Moody's de ayer. El movimiento del 20 de mayo de 2026 fue una rebaja, no una pérdida de categoría. Y Moody's cambió la perspectiva de negativa a estable, lo que en su propio lenguaje significa que no anticipa otra rebaja en los próximos 12–18 meses.

---

## Lo que los medios no te cuentan

**Asimetría uno: confundir la nota con la causa.** La calificación no es un agente económico autónomo. Es un resumen —bastante grueso— de la percepción de riesgo crediticio que ya está incorporada en los precios de los bonos. Cuando Moody's baja a Baa3, el mercado normalmente ya descontó esa información durante los meses previos. Por eso las degradaciones rara vez producen movimientos espectaculares en el tipo de cambio o en las tasas: el ajuste ocurrió antes. El titular llega tarde.

**Asimetría dos: ignorar a Pemex como el verdadero motor del deterioro.** Moody's estimó que el gobierno otorgó apoyos a Pemex por **USD 35 mil millones** en 2025 —equivalentes al 1.9% del PIB— y presupuestó otros USD 14 mil millones para 2026. Sin el agujero permanente de la petrolera estatal, el balance fiscal mexicano se vería radicalmente distinto y la calificación soberana estaría dos o tres escalones más arriba. Hablar del deterioro de la deuda sin hablar de Pemex es, literalmente, no hablar de la causa principal.

**Asimetría tres: no mencionar el costo de oportunidad, que es el verdaderamente alto.** Cada peso que el sector público destina a intereses es un peso que no va a infraestructura productiva, salud, educación o transferencias. Para 2026, el costo financiero será *igual* al endeudamiento nuevo del año (ambos 4.1% del PIB). Esto significa que México está prácticamente endeudándose sólo para pagar intereses —la definición técnica de una trampa fiscal lenta—. No es una crisis. Es una asfixia gradual.

---

## Conclusión

El costo real atribuible a la degradación de calificación, en sentido estricto, anda en el orden de **$50–90 mil millones de pesos anuales** —entre el 3.5% y el 6% del costo financiero total—. Importante, pero menos que dramático. El verdadero costo no aparece en los titulares: es la pérdida sostenida de margen fiscal frente al rescate permanente de Pemex y a un déficit estructural cuya consolidación se aplaza año tras año.

La nota crediticia es el síntoma; el cuerpo enfermo es la matriz fiscal mexicana de 2024 en adelante.

Para los inversionistas, la lectura útil es que México sigue siendo crédito de grado de inversión y probablemente lo seguirá siendo en el horizonte de pronóstico inmediato, aunque con costos crecientes. Para los analistas de política pública, la lectura útil es que el debate fiscal debería desplazarse del ruido de las calificadoras hacia la conversación sustantiva: **el costo financiero de la deuda ya supera el gasto en Bienestar más Educación combinados**. Esa frase debería repetirse hasta el cansancio en cualquier discusión seria sobre presupuesto público en México.

Lo demás es ruido.

---

#### Fuentes

1. *Moody's Ratings rebaja calificación crediticia de México de Baa2 a Baa3, cambia perspectiva de negativa a estable.* SHCP, comunicado del 20 de mayo de 2026; cobertura en El Universal, AM, Excélsior, Infobae.
2. *México juega con fuego en su calificación crediticia.* El Financiero, 19 de mayo de 2026.
3. *Tras rebaja de S&P, Moody's recortaría calificación de México en 2026: Banamex.* Investing.com, mayo de 2026.
4. *Fitch ratifica calificación de México en BBB− con perspectiva estable.* Comunicado SHCP No. 27, 10 de abril de 2026.
5. *El costo financiero de la deuda pública en México crece 5.1% en 2024 y alcanzará su nivel más alto en 25 años.* SHCP, citado en El Imparcial, 3 de febrero de 2025.
6. *Se pagan por intereses de la deuda 3 mil 516 mdp diarios.* La Jornada, 15 de noviembre de 2025.
7. *Informe sobre Finanzas Públicas y Deuda Pública 4T 2024.* SHCP. Tasas implícitas: 7.18% total, 7.48% interna, 5.56% externa.
8. *Deuda y presiones fiscales en los CGPE 2026.* Centro de Investigación Económica y Presupuestaria (CIEP), 2025.
9. *Riesgo país en América Latina al cierre de febrero 2026.* Revista Mercado / JPMorgan EMBI, marzo de 2026.
10. *Ley Federal de Presupuesto y Responsabilidad Hacendaria,* Cámara de Diputados, última reforma DOF 08-08-2025.

Las descomposiciones de sobrecosto de las Figuras 3 y 4 son estimaciones del autor con base en las fuentes anteriores. Comentarios y correcciones son bienvenidos.
