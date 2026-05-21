---
title: "El costo silencioso"
date: 2026-05-20
description: "Cuánto le ha costado realmente a México la degradación de su deuda soberana durante los últimos siete años — y por qué los titulares se equivocan al estimarlo."
tags: ["finanzas públicas", "deuda soberana", "macroeconomía", "calificadoras"]
showDate: false
showAuthor: false
showReadingTime: false
showTitle: false
showTableOfContents: false
---

{{< rawhtml >}}
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400&family=Crimson+Pro:wght@400;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
  .cs-wrap {
    --paper: #faf6ec;
    --paper-deep: #f3eddb;
    --ink: #1c1814;
    --ink-soft: #3a342c;
    --gray: #6b6353;
    --gray-light: #a39a87;
    --rule: #c9bea4;
    --rule-faint: #e0d7c0;
    --accent: #8b2c1d;
    --accent-soft: #b8543d;
    --highlight: #efe4c2;
    background: var(--paper);
    color: var(--ink);
    font-family: 'EB Garamond', Georgia, serif;
    line-height: 1.55;
    font-feature-settings: "kern", "liga", "onum";
    counter-reset: cs-section;
  }

  .cs-wrap * { box-sizing: border-box; }

  .cs-container {
    max-width: 720px;
    margin: 0 auto;
    padding: 60px 28px 100px;
  }

  .cs-wrap .masthead {
    border-bottom: 1px solid var(--rule);
    padding-bottom: 36px;
    margin-bottom: 48px;
  }

  .cs-wrap .kicker {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 24px;
    display: flex;
    gap: 14px;
    align-items: center;
    flex-wrap: wrap;
  }
  .cs-wrap .kicker .dot {
    width: 3px; height: 3px;
    background: var(--accent);
    border-radius: 50%;
    flex-shrink: 0;
  }

  .cs-wrap h1 {
    font-family: 'Crimson Pro', Georgia, serif;
    font-size: clamp(36px, 6vw, 52px);
    line-height: 1.05;
    font-weight: 700;
    letter-spacing: -0.02em;
    margin: 0 0 20px;
    color: var(--ink);
  }

  .cs-wrap .deck {
    font-family: 'EB Garamond', serif;
    font-style: italic;
    font-size: clamp(18px, 2.4vw, 22px);
    line-height: 1.4;
    color: var(--ink-soft);
    margin: 0 0 32px;
  }

  .cs-wrap .byline {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.06em;
    color: var(--gray);
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
  }
  .cs-wrap .byline span strong {
    color: var(--ink);
    font-weight: 500;
  }

  .cs-wrap p {
    margin: 0 0 1.2em;
    font-size: 18px;
    line-height: 1.65;
    color: var(--ink);
  }

  .cs-wrap p.lead::first-letter {
    font-family: 'Crimson Pro', serif;
    font-size: 64px;
    line-height: 0.85;
    float: left;
    padding: 6px 12px 0 0;
    font-weight: 700;
    color: var(--accent);
  }

  .cs-wrap h2 {
    font-family: 'Crimson Pro', serif;
    font-size: 28px;
    font-weight: 600;
    line-height: 1.2;
    margin: 56px 0 8px;
    color: var(--ink);
    letter-spacing: -0.01em;
    counter-increment: cs-section;
  }

  .cs-wrap h2::before {
    content: "§ " counter(cs-section);
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.1em;
    color: var(--accent);
    display: block;
    margin-bottom: 12px;
    font-weight: 400;
  }

  .cs-wrap h2 + .subhead {
    font-style: italic;
    color: var(--gray);
    margin-bottom: 28px;
    font-size: 16px;
  }

  .cs-wrap strong { font-weight: 600; color: var(--ink); }
  .cs-wrap em { font-style: italic; }

  .cs-wrap .number {
    font-family: 'JetBrains Mono', monospace;
    font-feature-settings: "tnum";
    font-size: 0.94em;
  }

  .cs-wrap .sidenote {
    font-size: 14px;
    line-height: 1.5;
    color: var(--gray);
    margin: 16px 0 28px;
    padding: 14px 18px 14px 20px;
    border-left: 2px solid var(--rule);
    background: var(--paper-deep);
    font-family: 'EB Garamond', serif;
    font-style: italic;
  }
  .cs-wrap .sidenote .num {
    font-family: 'JetBrains Mono', monospace;
    color: var(--accent);
    font-size: 10px;
    font-weight: 500;
    display: inline-block;
    margin-right: 10px;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    font-style: normal;
  }
  .cs-wrap .sidenote em { color: var(--ink-soft); font-style: normal; font-weight: 500; }

  .cs-wrap .sup {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    color: var(--accent);
    vertical-align: super;
    margin: 0 1px;
    font-weight: 600;
  }

  .cs-wrap blockquote {
    margin: 36px 0;
    padding: 0 0 0 22px;
    border-left: 2px solid var(--accent);
    font-family: 'Crimson Pro', serif;
    font-size: 20px;
    font-style: italic;
    line-height: 1.4;
    color: var(--ink-soft);
    background: none;
  }
  .cs-wrap blockquote cite {
    display: block;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    font-style: normal;
    letter-spacing: 0.06em;
    color: var(--gray);
    margin-top: 12px;
    text-transform: uppercase;
  }

  .cs-wrap .tufte-table {
    width: 100%;
    border-collapse: collapse;
    margin: 32px 0;
    font-size: 15px;
    font-family: 'EB Garamond', serif;
  }
  .cs-wrap .tufte-table caption {
    text-align: left;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--accent);
    padding-bottom: 12px;
    font-weight: 500;
  }
  .cs-wrap .tufte-table thead tr { border-bottom: 1px solid var(--ink); }
  .cs-wrap .tufte-table th {
    text-align: left;
    padding: 8px 12px 8px 0;
    font-family: 'EB Garamond', serif;
    font-weight: 600;
    font-size: 13px;
    color: var(--ink-soft);
    border: none;
    background: none;
  }
  .cs-wrap .tufte-table th.num, .cs-wrap .tufte-table td.num {
    text-align: right;
    font-family: 'JetBrains Mono', monospace;
    font-feature-settings: "tnum";
    font-size: 12px;
  }
  .cs-wrap .tufte-table tbody tr { border-bottom: 1px solid var(--rule-faint); }
  .cs-wrap .tufte-table tbody tr:last-child { border-bottom: 1px solid var(--ink); }
  .cs-wrap .tufte-table td {
    padding: 10px 12px 10px 0;
    vertical-align: top;
    background: none;
    color: var(--ink);
  }
  .cs-wrap .tufte-table tbody tr.highlight { background: var(--highlight); }
  .cs-wrap .tufte-table .small-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    color: var(--gray);
    letter-spacing: 0.04em;
  }

  .cs-wrap figure { margin: 40px 0; padding: 0; }
  .cs-wrap figure svg { display: block; width: 100%; height: auto; max-width: 100%; background: var(--paper); border-radius: 4px; }
  .cs-wrap figcaption {
    font-family: 'EB Garamond', serif;
    font-size: 13px;
    font-style: italic;
    color: var(--gray);
    margin-top: 12px;
    line-height: 1.5;
  }
  .cs-wrap figcaption strong {
    font-style: normal;
    color: var(--accent);
    font-weight: 600;
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    display: inline-block;
    margin-right: 6px;
  }

  .cs-wrap .legal-box {
    border: 1px solid var(--rule);
    background: var(--paper-deep);
    padding: 22px 24px;
    margin: 32px 0;
    font-size: 14px;
    line-height: 1.55;
  }
  .cs-wrap .legal-box .title {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 12px;
    font-weight: 500;
  }
  .cs-wrap .legal-box ul { margin: 0; padding-left: 18px; }
  .cs-wrap .legal-box li { margin-bottom: 8px; color: var(--ink); }

  .cs-wrap .refs {
    margin-top: 72px;
    padding-top: 36px;
    border-top: 1px solid var(--rule);
    font-size: 13px;
    line-height: 1.6;
    color: var(--gray);
  }
  .cs-wrap .refs h3 {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 16px;
    font-weight: 500;
  }
  .cs-wrap .refs h3::before { content: none; }
  .cs-wrap .refs ol { padding-left: 20px; margin: 0; }
  .cs-wrap .refs li { margin-bottom: 8px; font-family: 'EB Garamond', serif; color: var(--gray); }
  .cs-wrap .refs li em { color: var(--ink-soft); }

  .cs-wrap .keystats {
    background: var(--ink);
    color: var(--paper);
    padding: 28px;
    margin: 36px 0;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 24px;
  }
  .cs-wrap .keystats .stat .label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 9px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--gray-light);
    margin-bottom: 6px;
  }
  .cs-wrap .keystats .stat .value {
    font-family: 'Crimson Pro', serif;
    font-size: 30px;
    font-weight: 700;
    line-height: 1;
    color: var(--paper);
  }
  .cs-wrap .keystats .stat .unit {
    font-family: 'EB Garamond', serif;
    font-size: 12px;
    font-style: italic;
    color: var(--gray-light);
    margin-top: 4px;
  }

  .cs-wrap .takeaway {
    border-top: 2px solid var(--ink);
    border-bottom: 2px solid var(--ink);
    padding: 26px 0;
    margin: 48px 0;
  }
  .cs-wrap .takeaway .label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 10px;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 12px;
    font-weight: 500;
  }
  .cs-wrap .takeaway p {
    font-family: 'Crimson Pro', serif;
    font-size: 21px;
    line-height: 1.4;
    margin: 0;
    font-weight: 400;
    color: var(--ink);
  }

  .cs-wrap a { color: var(--accent); text-decoration: none; border-bottom: 1px solid var(--accent-soft); }
  .cs-wrap a:hover { background: var(--highlight); }

  .cs-wrap .ornament {
    text-align: center;
    margin: 48px 0;
    color: var(--rule);
    font-size: 14px;
    letter-spacing: 0.8em;
  }
</style>

<div class="cs-wrap">
<article class="cs-container">

<header class="masthead">
  <div class="kicker">
    <span>Análisis macrofiscal</span>
    <span class="dot"></span>
    <span>Deuda soberana</span>
    <span class="dot"></span>
    <span>20 mayo 2026</span>
  </div>
  <h1>El costo silencioso</h1>
  <p class="deck">Cuánto le ha costado realmente a México la degradación de su deuda soberana durante los últimos siete años — y por qué los titulares se equivocan al estimarlo.</p>
  <div class="byline">
    <span><strong>Benjamín Barragán Abad</strong></span>
    <span>Río Blanco, Veracruz</span>
    <span>Lectura: 14 min</span>
  </div>
</header>

<p class="lead">Cada vez que una agencia calificadora ajusta a la baja la nota soberana de México, el ciclo mediático se repite con previsibilidad de manual: titulares en mayúsculas, comparaciones con países en crisis, y muy poco esfuerzo serio por traducir el cambio en pesos contantes. Hoy mismo, <strong>20 de mayo de 2026, Moody's redujo la calificación de México de Baa2 a Baa3</strong><span class="sup">1</span>, dejando al país a un solo escalón del límite del grado de inversión. La pregunta que casi nadie responde es la única que importa: <em>¿cuánto cuesta esto en dinero real?</em></p>

<aside class="sidenote"><span class="num">Nota 1</span> La acción de Moody's del 20 de mayo de 2026 rebajó la nota a <em>Baa3</em>, el último escalón antes del grado especulativo. La perspectiva pasó de <em>negativa</em> a <em>estable</em>. SHCP destacó que México conserva grado de inversión con las ocho agencias que lo evalúan.</aside>

<p>Este artículo intenta llenar ese hueco. Reconstruye la cronología completa de degradaciones desde 2019, cuantifica el costo financiero efectivo de la deuda pública mexicana, descompone qué porcentaje de ese costo es atribuible específicamente a las rebajas de calificación, y proyecta los escenarios reales — no los retóricos — en los que México podría perder el grado de inversión.</p>

<p>La conclusión, anticipada para quienes prefieren el resumen: el sobrecosto directamente atribuible a la degradación es modesto, entre <span class="number">4%</span> y <span class="number">6%</span> del costo financiero total. Lo verdaderamente caro no es la nota crediticia. Es lo que la nota refleja.</p>

<div class="keystats">
  <div class="stat">
    <div class="label">Costo financiero 2026</div>
    <div class="value">$1.55<span style="font-size:18px">B</span></div>
    <div class="unit">billones MXN · 4.1% PIB</div>
  </div>
  <div class="stat">
    <div class="label">Pago diario intereses</div>
    <div class="value">$3,517</div>
    <div class="unit">MDP al día (2025)</div>
  </div>
  <div class="stat">
    <div class="label">Deuda bruta / PIB</div>
    <div class="value">49.3%</div>
    <div class="unit">en 2025, desde 35.4% en 2018</div>
  </div>
  <div class="stat">
    <div class="label">EMBI México</div>
    <div class="value">226<span style="font-size:18px">pb</span></div>
    <div class="unit">cierre febrero 2026</div>
  </div>
</div>

<h2>Cronología de un descenso</h2>
<p class="subhead">Siete años, ocho movimientos, cero gritos.</p>

<p>Para dimensionar el deterioro hay que recordar el punto de partida. A finales de 2018, México llegó al cambio de gobierno con tres calificaciones distintas, todas dos o tres escalones por encima del umbral del grado de inversión: <span class="number">A3</span> en Moody's, <span class="number">BBB+</span> en S&amp;P y <span class="number">BBB+</span> en Fitch. Era el techo histórico para el país y reflejaba dos décadas de mejora ininterrumpida desde la salida del tequila.</p>

<p>El descenso comenzó en 2019 con un movimiento poco celebrado: HR Ratings, la única calificadora reconocida mexicana, bajó por primera vez en su historia la nota soberana del país que la albergaba<span class="sup">2</span>. A partir de ahí, el descenso fue ordenado pero persistente.</p>

<aside class="sidenote"><span class="num">Nota 2</span> Primera vez en la historia que la calificadora mexicana bajó la nota soberana de su propio país. Marcó el inicio del ciclo de descenso.</aside>

<figure>
<svg viewBox="0 0 800 320" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
  <rect width="800" height="320" fill="#faf6ec"/>
  <defs><style>.cs-axis{stroke:#1c1814;stroke-width:1;fill:none}.cs-label-yr{font-family:monospace;font-size:10px;fill:#6b6353}.cs-label-ag{font-family:serif;font-size:11px;fill:#3a342c}.cs-label-act{font-family:serif;font-size:10px;fill:#6b6353;font-style:italic}.cs-level{font-family:monospace;font-size:10px;fill:#1c1814;font-weight:500}.cs-grade-line{stroke:#c9bea4;stroke-width:.5;stroke-dasharray:2,3}.cs-danger{stroke:#8b2c1d;stroke-width:1;stroke-dasharray:3,3}.cs-dot-m{fill:#8b2c1d}.cs-dot-s{fill:#1c1814}.cs-dot-f{fill:#2d5a3d}.cs-path-m{stroke:#8b2c1d;stroke-width:1.4;fill:none}.cs-path-s{stroke:#1c1814;stroke-width:1.4;fill:none}.cs-path-f{stroke:#2d5a3d;stroke-width:1.4;fill:none}.cs-legend-text{font-family:serif;font-size:11px;fill:#3a342c}</style></defs>
  <line class="cs-axis" x1="100" y1="260" x2="760" y2="260"/>
  <g class="cs-label-yr">
    <text x="100" y="280" text-anchor="middle">2018</text>
    <text x="183" y="280" text-anchor="middle">2019</text>
    <text x="265" y="280" text-anchor="middle">2020</text>
    <text x="348" y="280" text-anchor="middle">2021</text>
    <text x="430" y="280" text-anchor="middle">2022</text>
    <text x="513" y="280" text-anchor="middle">2023</text>
    <text x="595" y="280" text-anchor="middle">2024</text>
    <text x="678" y="280" text-anchor="middle">2025</text>
    <text x="760" y="280" text-anchor="middle">2026</text>
  </g>
  <line class="cs-grade-line" x1="100" y1="60" x2="760" y2="60"/>
  <text class="cs-level" x="95" y="63" text-anchor="end">A3 / A−</text>
  <line class="cs-grade-line" x1="100" y1="100" x2="760" y2="100"/>
  <text class="cs-level" x="95" y="103" text-anchor="end">Baa1 / BBB+</text>
  <line class="cs-grade-line" x1="100" y1="140" x2="760" y2="140"/>
  <text class="cs-level" x="95" y="143" text-anchor="end">Baa2 / BBB</text>
  <line class="cs-danger" x1="100" y1="180" x2="760" y2="180"/>
  <text class="cs-level" x="95" y="183" text-anchor="end" fill="#8b2c1d">Baa3 / BBB−</text>
  <line class="cs-grade-line" x1="100" y1="220" x2="760" y2="220"/>
  <text class="cs-level" x="95" y="223" text-anchor="end">Ba1 / BB+</text>
  <text class="cs-label-act" x="660" y="195">grado de inversión</text>
  <text class="cs-label-act" x="660" y="235">especulativo</text>
  <polyline class="cs-path-m" points="100,60 250,60 250,100 430,100 430,140 760,140 760,180"/>
  <circle class="cs-dot-m" cx="100" cy="60" r="3.5"/>
  <circle class="cs-dot-m" cx="250" cy="100" r="3.5"/>
  <circle class="cs-dot-m" cx="430" cy="140" r="3.5"/>
  <circle class="cs-dot-m" cx="760" cy="180" r="3.5"/>
  <polyline class="cs-path-s" points="100,100 248,100 248,140 760,140"/>
  <circle class="cs-dot-s" cx="100" cy="100" r="3.5"/>
  <circle class="cs-dot-s" cx="248" cy="140" r="3.5"/>
  <circle class="cs-dot-s" cx="755" cy="140" r="3.5"/>
  <polyline class="cs-path-f" points="100,100 165,100 165,140 253,140 253,180 760,180"/>
  <circle class="cs-dot-f" cx="100" cy="100" r="3.5"/>
  <circle class="cs-dot-f" cx="165" cy="140" r="3.5"/>
  <circle class="cs-dot-f" cx="253" cy="180" r="3.5"/>
  <circle class="cs-dot-f" cx="750" cy="180" r="3.5"/>
  <g class="cs-label-ag">
    <text x="255" y="115" fill="#8b2c1d">Moody's → Baa1</text>
    <text x="435" y="155" fill="#8b2c1d">Moody's → Baa2</text>
    <text x="640" y="200" fill="#8b2c1d" font-weight="500">Baa3 — hoy</text>
  </g>
  <g transform="translate(100, 18)">
    <line x1="0" y1="0" x2="20" y2="0" class="cs-path-m"/>
    <circle class="cs-dot-m" cx="10" cy="0" r="3"/>
    <text class="cs-legend-text" x="28" y="3">Moody's</text>
    <line x1="100" y1="0" x2="120" y2="0" class="cs-path-s"/>
    <circle class="cs-dot-s" cx="110" cy="0" r="3"/>
    <text class="cs-legend-text" x="128" y="3">S&amp;P</text>
    <line x1="180" y1="0" x2="200" y2="0" class="cs-path-f"/>
    <circle class="cs-dot-f" cx="190" cy="0" r="3"/>
    <text class="cs-legend-text" x="208" y="3">Fitch</text>
  </g>
</svg>
<figcaption><strong>Figura 1</strong> Trayectoria de la calificación soberana de México, 2018–2026. Las tres agencias principales convergieron hacia el límite inferior del grado de inversión a un ritmo distinto, pero en la misma dirección. La rebaja del 20 de mayo de 2026 deja a México con Moody's en el último notch antes de perder el grado de inversión.</figcaption>
</figure>

<p>El detalle importa: <strong>Moody's bajó cuatro escalones</strong> desde A3 en 2018 hasta Baa3 hoy. <strong>S&amp;P perdió uno y entró en perspectiva negativa</strong> el 12 de mayo de 2026<span class="sup">3</span>. <strong>Fitch perdió dos</strong> y ratificó BBB− con perspectiva estable el 10 de abril de 2026<span class="sup">4</span>. La fotografía actual es la de un país en el último piso del grado de inversión con dos calificadoras de las tres principales.</p>

<aside class="sidenote"><span class="num">Notas 3 y 4</span> S&amp;P citó déficit fiscal estimado en 4.9% del PIB y proyección de deuda neta en 54% PIB para 2029. Fitch reconoció marco macroeconómico prudente y cuentas externas robustas; identificó como riesgos el bajo crecimiento potencial, debilidades institucionales y pasivos contingentes de Pemex.</aside>

<table class="tufte-table">
  <caption>Calificación soberana de México: trayectoria comparada</caption>
  <thead>
    <tr>
      <th>Año</th>
      <th>Moody's</th>
      <th>S&amp;P</th>
      <th>Fitch</th>
      <th class="num">Evento clave</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>2018</td><td>A3</td><td>BBB+</td><td>BBB+</td><td class="num small-label">techo histórico</td></tr>
    <tr><td>2019</td><td>A3</td><td>BBB+</td><td>BBB</td><td class="num small-label">HR baja soberano</td></tr>
    <tr><td>2020</td><td>Baa1</td><td>BBB</td><td>BBB−</td><td class="num small-label">COVID + Pemex</td></tr>
    <tr><td>2022</td><td>Baa2</td><td>BBB</td><td>BBB−</td><td class="num small-label">deterioro fiscal</td></tr>
    <tr><td>2024</td><td>Baa2 ▼</td><td>BBB</td><td>BBB−</td><td class="num small-label">Moody's: persp. neg</td></tr>
    <tr class="highlight"><td>2026</td><td>Baa3</td><td>BBB ▼</td><td>BBB−</td><td class="num small-label">situación actual</td></tr>
  </tbody>
</table>

<div class="ornament">· · ·</div>

<h2>Lo que cuesta en dinero real</h2>
<p class="subhead">El costo financiero como porcentaje del PIB, en perspectiva.</p>

<p>El costo financiero de la deuda pública no es la calificación. Es el monto efectivamente pagado en intereses y comisiones para sostener el servicio del pasivo. La Ley Federal de Presupuesto y Responsabilidad Hacendaria lo reporta cada trimestre y lo presupuesta cada año. El dato es público y duro.</p>

<p>En 2018, México pagaba aproximadamente <span class="number">$620 mil millones de pesos</span> al año por concepto de intereses, lo que equivalía a <span class="number">2.5%</span> del PIB. Para 2024, el monto subió a <span class="number">$1.15 billones</span> — un incremento real de <span class="number">5.1%</span> respecto al año anterior — y para 2025 alcanzó <span class="number">$1.39 billones</span><span class="sup">5</span>. La SHCP proyecta para 2026 un costo de <span class="number">$1.55 billones</span>, equivalente al <span class="number">4.1%</span> del PIB. Es el nivel más alto desde el año 2000.</p>

<figure>
<svg viewBox="0 0 760 300" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
  <rect width="760" height="300" fill="#faf6ec"/>
  <defs><style>.cs-bar{fill:#8b2c1d}.cs-bar-hist{fill:#c9bea4}.cs-yax{font-family:monospace;font-size:10px;fill:#6b6353}.cs-xax{font-family:monospace;font-size:11px;fill:#1c1814}.cs-val{font-family:monospace;font-size:10px;fill:#1c1814;font-weight:500}.cs-ref{stroke:#c9bea4;stroke-width:.5;stroke-dasharray:2,3}.cs-ref-lbl{font-family:serif;font-size:11px;fill:#8b2c1d;font-style:italic}</style></defs>
  <line class="cs-ref" x1="60" y1="220" x2="730" y2="220"/>
  <line class="cs-ref" x1="60" y1="170" x2="730" y2="170"/>
  <line class="cs-ref" x1="60" y1="120" x2="730" y2="120"/>
  <text class="cs-yax" x="55" y="223" text-anchor="end">2%</text>
  <text class="cs-yax" x="55" y="173" text-anchor="end">3%</text>
  <text class="cs-yax" x="55" y="123" text-anchor="end">4%</text>
  <line stroke="#8b2c1d" stroke-width="0.5" stroke-dasharray="3,3" x1="60" y1="220" x2="730" y2="220"/>
  <text class="cs-ref-lbl" x="725" y="216" text-anchor="end">nivel 2018 ─ 2.5% PIB</text>
  <rect class="cs-bar-hist" x="80" y="145" width="60" height="125"/>
  <text class="cs-val" x="110" y="138" text-anchor="middle">2.5</text>
  <text class="cs-xax" x="110" y="290" text-anchor="middle">'18</text>
  <rect class="cs-bar-hist" x="155" y="140" width="60" height="130"/>
  <text class="cs-val" x="185" y="133" text-anchor="middle">2.6</text>
  <text class="cs-xax" x="185" y="290" text-anchor="middle">'19</text>
  <rect class="cs-bar-hist" x="230" y="140" width="60" height="130"/>
  <text class="cs-val" x="260" y="133" text-anchor="middle">2.6</text>
  <text class="cs-xax" x="260" y="290" text-anchor="middle">'20</text>
  <rect class="cs-bar-hist" x="305" y="145" width="60" height="125"/>
  <text class="cs-val" x="335" y="138" text-anchor="middle">2.5</text>
  <text class="cs-xax" x="335" y="290" text-anchor="middle">'21</text>
  <rect class="cs-bar-hist" x="380" y="130" width="60" height="140"/>
  <text class="cs-val" x="410" y="123" text-anchor="middle">2.8</text>
  <text class="cs-xax" x="410" y="290" text-anchor="middle">'22</text>
  <rect class="cs-bar-hist" x="455" y="135" width="60" height="135"/>
  <text class="cs-val" x="485" y="128" text-anchor="middle">2.7</text>
  <text class="cs-xax" x="485" y="290" text-anchor="middle">'23</text>
  <rect class="cs-bar" x="530" y="85" width="60" height="185"/>
  <text class="cs-val" x="560" y="78" text-anchor="middle">3.7</text>
  <text class="cs-xax" x="560" y="290" text-anchor="middle">'24</text>
  <rect class="cs-bar" x="605" y="80" width="60" height="190"/>
  <text class="cs-val" x="635" y="73" text-anchor="middle">3.8</text>
  <text class="cs-xax" x="635" y="290" text-anchor="middle">'25</text>
  <rect class="cs-bar" x="680" y="65" width="50" height="205" fill-opacity="0.6" fill="#8b2c1d"/>
  <text class="cs-val" x="705" y="58" text-anchor="middle">4.1</text>
  <text class="cs-xax" x="705" y="290" text-anchor="middle">'26*</text>
</svg>
<figcaption><strong>Figura 2</strong> Costo financiero de la deuda pública mexicana como porcentaje del PIB, 2018–2026. El asterisco (2026) indica cifra presupuestada en el Paquete Económico. La aceleración se concentra a partir de 2024 y refleja la combinación de tasas globales más altas, mayor stock de deuda y absorción del rescate de Pemex.</figcaption>
</figure>

<blockquote>
"El costo financiero de la deuda llegará a 1.39 billones de pesos en 2025, monto que equivale al 14.2% del gasto neto estimado para ese año."
<cite>SHCP — Criterios Generales de Política Económica 2025</cite>
</blockquote>

<p>Traducido a un horizonte cotidiano: durante 2025, el sector público mexicano gastó en promedio <span class="number">$3,516.7 millones de pesos al día</span> solo en intereses<span class="sup">6</span>. Esa cifra es <strong>68.8% mayor</strong> que lo destinado a obra pública en el mismo periodo. El costo financiero supera, por sí solo, el presupuesto combinado de las secretarías de Bienestar y Educación Pública para el ejercicio 2025.</p>

<aside class="sidenote"><span class="num">Nota 6</span> En el mismo periodo, la obra pública cayó 32.5% interanual, mientras que el costo financiero subió 8.6%.</aside>

<p>El problema no es que México pague intereses — todos los países lo hacen. El problema es la trayectoria. La razón <em>costo financiero / gasto neto</em> pasó de <span class="number">9.1%</span> en 2018 a <span class="number">14.2%</span> en 2025, y el Paquete Económico 2026 estima que llegará a <span class="number">15%</span> el próximo año. Esto significa que <strong>uno de cada siete pesos del presupuesto federal se destina a pagar intereses</strong>, antes de ejecutar política pública alguna.</p>

<h2>El marco legal: qué obliga y qué no</h2>
<p class="subhead">Por qué la trayectoria importa para los acreedores y las calificadoras.</p>

<div class="legal-box">
  <div class="title">Andamiaje normativo de la deuda pública mexicana</div>
  <ul>
    <li><strong>Constitución, Art. 73 fracción VIII.</strong> Facultad exclusiva del Congreso para autorizar el endeudamiento del Ejecutivo Federal.</li>
    <li><strong>Constitución, Art. 74 fracción IV.</strong> Facultad exclusiva de la Cámara de Diputados para aprobar el Presupuesto de Egresos y revisar la Cuenta Pública.</li>
    <li><strong>Ley General de Deuda Pública</strong>, que regula la contratación, refinanciamiento y registro de obligaciones del sector público federal.</li>
    <li><strong>LFPRH, Art. 17.</strong> Obliga al Ejecutivo a programar el gasto de forma que contribuya al equilibrio presupuestario y a la meta de Requerimientos Financieros del Sector Público (RFSP).</li>
    <li><strong>LFPRH, Art. 2 fracciones XLVII y XLIX.</strong> Define los RFSP como variable de flujo y el SHRFSP (Saldo Histórico) como variable de stock — los indicadores principales que las calificadoras monitorean.</li>
  </ul>
</div>

<p>El detalle institucional relevante: la regla de equilibrio del Art. 17 de la LFPRH no es jurídicamente vinculante en términos sancionatorios. Se trata de una obligación de programación y reporte, no de un techo constitucional al estilo de la <em>Schuldenbremse</em> alemana o de las reglas de Maastricht. La SHCP puede desviarse de la meta original siempre que lo informe al Congreso. Esto es importante: explica por qué las calificadoras han bajado la nota incluso cuando el gobierno reporta "cumplimiento del marco legal".</p>

<div class="ornament">· · ·</div>

<h2>Descomposición del sobrecosto</h2>
<p class="subhead">Cuánto del incremento es atribuible a la calificación, cuánto a otros factores.</p>

<p>Aquí está la pregunta que los titulares evaden: del aumento de <span class="number">1.6 puntos del PIB</span> en el costo financiero entre 2018 y 2026, ¿cuánto se debe específicamente a la degradación de calificación y cuánto a otros factores? Una descomposición razonable, basada en las tasas implícitas reportadas por SHCP<span class="sup">7</span> y en el comportamiento del EMBI México, arroja lo siguiente:</p>

<aside class="sidenote"><span class="num">Nota 7</span> Las tasas implícitas se calculan como costo financiero efectivo dividido entre el saldo promedio del stock de deuda en cada moneda. SHCP reportó al 4T 2024: 7.18% total, 7.48% interna, 5.56% externa.</aside>

<figure>
<svg viewBox="0 0 760 240" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
  <rect width="760" height="240" fill="#faf6ec"/>
  <defs><style>.cs-lcat{font-family:serif;font-size:13px;fill:#1c1814}.cs-lval{font-family:monospace;font-size:11px;fill:#1c1814;font-weight:500}.cs-lpct{font-family:monospace;font-size:10px;fill:#6b6353}.cs-bext{fill:#c9bea4}.cs-bcrd{fill:#8b2c1d}.cs-axl{stroke:#6b6353;stroke-width:.5}</style></defs>
  <g transform="translate(0,20)">
    <text class="cs-lcat" x="270" y="14">Tasas globales (Fed funds + treasuries)</text>
    <rect class="cs-bext" x="280" y="22" width="325" height="18"/>
    <text class="cs-lval" x="610" y="35">+250 pb · 60%</text>
  </g>
  <g transform="translate(0,65)">
    <text class="cs-lcat" x="270" y="14">Inflación interna (paso a Cetes)</text>
    <rect class="cs-bext" x="280" y="22" width="108" height="18"/>
    <text class="cs-lval" x="395" y="35">+85 pb · 20%</text>
  </g>
  <g transform="translate(0,110)">
    <text class="cs-lcat" x="270" y="14">Déficit fiscal estructural + Pemex</text>
    <rect class="cs-bext" x="280" y="22" width="80" height="18"/>
    <text class="cs-lval" x="370" y="35">+65 pb · 15%</text>
  </g>
  <g transform="translate(0,155)">
    <text class="cs-lcat" x="270" y="14" font-weight="600" fill="#8b2c1d">Degradación de calificación per se</text>
    <rect class="cs-bcrd" x="280" y="22" width="28" height="18"/>
    <text class="cs-lval" x="320" y="35">+22 pb · 5%</text>
  </g>
  <line class="cs-axl" x1="280" y1="200" x2="610" y2="200"/>
  <text class="cs-lpct" x="280" y="215" text-anchor="start">0 pb</text>
  <text class="cs-lpct" x="445" y="215" text-anchor="middle">200 pb</text>
  <text class="cs-lpct" x="610" y="215" text-anchor="end">~420 pb sobrecosto total</text>
</svg>
<figcaption><strong>Figura 3</strong> Descomposición estimada del incremento en el costo de financiamiento mexicano, 2018–2026. Estimación propia con base en EMBI México (JPMorgan), tasas implícitas SHCP y movimientos de Fed funds rate. Sólo aproximadamente <span class="number">5%</span> del sobrecosto es atribuible directamente a las degradaciones de calificación; el grueso responde a factores globales y al deterioro fiscal interno que las calificaciones <em>reflejan</em>, no causan.</figcaption>
</figure>

<p>Tres lecturas se derivan de esta descomposición:</p>

<p>Primera: el ciclo global de tasas de interés explica el grueso del aumento. La Fed pasó de <span class="number">0.25%</span> en 2021 a <span class="number">5.25%</span> en 2023, y aunque ya inició su descenso, todavía se encuentra cerca de <span class="number">4.25%</span> en 2026. Cualquier país emergente — con o sin degradación — vio subir su costo de financiamiento en proporciones comparables.</p>

<p>Segunda: el premio por riesgo crediticio puramente atribuible a las degradaciones es del orden de <span class="number">20–30 puntos base</span>. Sobre el stock de deuda externa mexicana (~<span class="number">USD 240 mil millones</span>), eso equivale a un sobrecosto anual de aproximadamente <span class="number">USD 600 millones</span>, o cerca de <span class="number">$11 mil millones de pesos</span>. Es real, pero representa menos del <span class="number">1%</span> del costo financiero total.</p>

<p>Tercera, y más importante: el premio por <em>fundamentos fiscales deteriorados</em> es mucho mayor que el premio por la nota crediticia. Los inversionistas no esperan a que Moody's actúe; reaccionan en tiempo real a los datos de SHCP, al precio del petróleo, a las inyecciones a Pemex y al perfil del paquete económico. La calificadora llega después.</p>

<h2>Comparación regional</h2>
<p class="subhead">El espejo en el que México se mira.</p>

<p>Para tener una sensación calibrada del costo, conviene comparar el EMBI mexicano con el de sus pares regionales. El EMBI mide la diferencia de rendimiento, en puntos base, entre los bonos soberanos de un país y los Treasuries estadounidenses al mismo plazo. Cien puntos base equivalen a un punto porcentual de sobrecosto anual.</p>

<figure>
<svg viewBox="0 0 760 260" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="xMidYMid meet">
  <rect width="760" height="260" fill="#faf6ec"/>
  <defs><style>.cs-dr{fill:#1c1814}.cs-dmx{fill:#8b2c1d}.cs-cl{font-family:serif;font-size:14px;fill:#1c1814}.cs-clmx{font-family:serif;font-size:14px;fill:#8b2c1d;font-weight:600}.cs-vl{font-family:monospace;font-size:11px;fill:#1c1814}.cs-vlmx{font-family:monospace;font-size:11px;fill:#8b2c1d;font-weight:600}.cs-rl{font-family:monospace;font-size:10px;fill:#6b6353}.cs-sl{stroke:#c9bea4;stroke-width:.5;stroke-dasharray:2,3}.cs-sc{font-family:monospace;font-size:10px;fill:#6b6353}</style></defs>
  <line class="cs-sl" x1="200" y1="40" x2="200" y2="230"/>
  <line class="cs-sl" x1="349" y1="40" x2="349" y2="230"/>
  <line class="cs-sl" x1="498" y1="40" x2="498" y2="230"/>
  <line class="cs-sl" x1="647" y1="40" x2="647" y2="230"/>
  <text class="cs-sc" x="200" y="248" text-anchor="middle">0</text>
  <text class="cs-sc" x="349" y="248" text-anchor="middle">200</text>
  <text class="cs-sc" x="498" y="248" text-anchor="middle">400</text>
  <text class="cs-sc" x="647" y="248" text-anchor="middle">600 pb</text>
  <g transform="translate(0,25)">
    <text class="cs-cl" x="20" y="0">Uruguay</text>
    <text class="cs-rl" x="20" y="14">BBB+ · estable</text>
    <circle class="cs-dr" cx="255" cy="6" r="4"/>
    <text class="cs-vl" x="265" y="10">74</text>
  </g>
  <g transform="translate(0,60)">
    <text class="cs-cl" x="20" y="0">Chile</text>
    <text class="cs-rl" x="20" y="14">A · estable</text>
    <circle class="cs-dr" cx="277" cy="6" r="4"/>
    <text class="cs-vl" x="287" y="10">104</text>
  </g>
  <g transform="translate(0,95)">
    <text class="cs-cl" x="20" y="0">Perú</text>
    <text class="cs-rl" x="20" y="14">BBB · estable</text>
    <circle class="cs-dr" cx="289" cy="6" r="4"/>
    <text class="cs-vl" x="299" y="10">120</text>
  </g>
  <g transform="translate(0,130)">
    <text class="cs-cl" x="20" y="0">Brasil</text>
    <text class="cs-rl" x="20" y="14">BB · estable</text>
    <circle class="cs-dr" cx="348" cy="6" r="4"/>
    <text class="cs-vl" x="358" y="10">199</text>
  </g>
  <g transform="translate(0,165)">
    <text class="cs-clmx" x="20" y="0">México</text>
    <text class="cs-rl" x="20" y="14" fill="#8b2c1d">BBB / Baa3 · negativa</text>
    <circle class="cs-dmx" cx="368" cy="6" r="5"/>
    <text class="cs-vlmx" x="378" y="10">226</text>
  </g>
  <g transform="translate(0,200)">
    <text class="cs-cl" x="20" y="0">Colombia</text>
    <text class="cs-rl" x="20" y="14">BB+ · negativa</text>
    <circle class="cs-dr" cx="419" cy="6" r="4"/>
    <text class="cs-vl" x="429" y="10">294</text>
  </g>
</svg>
<figcaption><strong>Figura 4</strong> Riesgo país (EMBI, JPMorgan) en América Latina al cierre de febrero 2026. México paga <span class="number">+122 pb</span> más que Chile por financiamiento comparable, lo que se traduce — sobre la deuda externa de <span class="number">USD 240 mil millones</span> — en aproximadamente <span class="number">USD 2,930 millones anuales</span> de sobrecosto frente al "país BBB modelo" de la región.</figcaption>
</figure>

<p>Esta es la cifra honesta: México paga aproximadamente <span class="number">$54 mil millones de pesos</span> más al año por su servicio externo de lo que pagaría si tuviera el perfil crediticio de Chile. Es real, es relevante, y representa cerca del <span class="number">3.5%</span> del costo financiero total. Ese es el verdadero precio de oportunidad de la trayectoria 2018–2026, no las cifras catastrofistas que circulan en redes.</p>

<div class="ornament">· · ·</div>

<h2>El escenario que sí importaría</h2>
<p class="subhead">Qué pasa si se pierde el grado de inversión.</p>

<p>Lo expuesto hasta aquí asume continuidad. El cálculo cambia radicalmente si Moody's vuelve a actuar y baja a Ba1, o si S&amp;P concreta su perspectiva negativa y mueve a BB+. En ambos casos, México perdería el grado de inversión con dos de las tres calificadoras grandes, lo que activa un mecanismo de venta forzosa por parte de fondos institucionales globales restringidos por mandato a invertir solo en deuda investment grade.</p>

<table class="tufte-table">
  <caption>Impacto estimado si México pierde el grado de inversión</caption>
  <thead>
    <tr>
      <th>Efecto</th>
      <th class="num">Magnitud</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Salida forzosa de índices globales (GBI-EM, WGBI)</td><td class="num">USD 30–45 mil M</td></tr>
    <tr><td>Incremento estructural de spread soberano</td><td class="num">+150 a +300 pb</td></tr>
    <tr><td>Sobrecosto anual incremental en deuda nueva</td><td class="num">$80–150 mil MDP</td></tr>
    <tr><td>Encarecimiento corporativo por <em>sovereign ceiling</em></td><td class="num">Pemex, CFE, AMX</td></tr>
    <tr><td>Depreciación cambiaria estimada (6 meses)</td><td class="num">+8% a +15% MXN/USD</td></tr>
    <tr><td>Inflación importada (efecto traspaso)</td><td class="num">+0.8 a +1.5 pp</td></tr>
  </tbody>
</table>

<p>Estos números son cualitativamente distintos a los que hemos venido manejando. La diferencia entre Baa3 y Ba1 es la diferencia entre ajustes contables y ajuste macroeconómico discreto. La pérdida del grado de inversión no es un escenario lineal de "<em>un peldaño más</em>"; es un umbral con efectos no lineales en el portafolio internacional de bonos mexicanos.</p>

<p>La buena noticia, si así puede llamarse: hoy esa pérdida no es inminente. <strong>México conserva el grado de inversión con las ocho agencias que evalúan su deuda soberana</strong>, según señaló la propia SHCP en su comunicado sobre la acción de Moody's de hoy<span class="sup">8</span>. El movimiento del 20 de mayo de 2026 fue una rebaja, no una pérdida de categoría. Y Moody's cambió la perspectiva de negativa a estable, lo que en su propio lenguaje significa que no anticipa otra rebaja en los próximos 12–18 meses.</p>

<aside class="sidenote"><span class="num">Nota 8</span> Las ocho agencias son: Moody's, S&amp;P, Fitch, DBRS, JCR (Japón), R&amp;I (Japón), HR Ratings y Scope (Europa). El consenso — todas en grado de inversión — es lo que ancla el acceso de México a inversionistas institucionales globales.</aside>

<h2>Lo que los medios no te cuentan</h2>
<p class="subhead">Tres asimetrías analíticas frecuentes en la cobertura.</p>

<p><strong>Asimetría uno: confundir la nota con la causa.</strong> La calificación no es un agente económico autónomo. Es un resumen — bastante grueso — de la percepción de riesgo crediticio que ya está incorporada en los precios de los bonos. Cuando Moody's baja a Baa3, el mercado normalmente ya descontó esa información durante los meses previos. Por eso las degradaciones rara vez producen movimientos espectaculares en el tipo de cambio o en las tasas: el ajuste ocurrió antes. El titular llega tarde.</p>

<p><strong>Asimetría dos: ignorar a Pemex como el verdadero motor del deterioro.</strong> Moody's estimó que el gobierno otorgó apoyos a Pemex por <span class="number">USD 35 mil millones</span> en 2025 — equivalentes al <span class="number">1.9%</span> del PIB — y presupuestó otros <span class="number">USD 14 mil millones</span> para 2026<span class="sup">9</span>. Sin el agujero permanente de la petrolera estatal, el balance fiscal mexicano se vería radicalmente distinto y la calificación soberana estaría dos o tres escalones más arriba. Hablar del deterioro de la deuda sin hablar de Pemex es, literalmente, no hablar de la causa principal.</p>

<aside class="sidenote"><span class="num">Nota 9</span> Equivalentes al 1.9% del PIB en 2025 y 0.7% en 2026 (presupuestado). Moody's anticipa que estos apoyos continuarán a falta de mejora operativa material en la petrolera.</aside>

<p><strong>Asimetría tres: no mencionar el costo de oportunidad, que es el verdaderamente alto.</strong> Cada peso que el sector público destina a intereses es un peso que no va a infraestructura productiva, salud, educación o transferencias. Para 2026, el costo financiero será <em>igual</em> al endeudamiento nuevo del año (ambos <span class="number">4.1%</span> del PIB)<span class="sup">10</span>. Esto significa que México está prácticamente endeudándose sólo para pagar intereses — la definición técnica de una trampa fiscal lenta. No es una crisis. Es una asfixia gradual.</p>

<aside class="sidenote"><span class="num">Nota 10</span> Cuando el costo financiero iguala al endeudamiento nuevo, el déficit primario se vuelve estructuralmente irrelevante: el país se endeuda solo para pagar intereses. Análisis del CIEP sobre CGPE 2026.</aside>

<div class="takeaway">
  <div class="label">Conclusión</div>
  <p>El costo real atribuible a la degradación de calificación, en sentido estricto, anda en el orden de <span class="number">$50–90 mil millones de pesos anuales</span> — entre el <span class="number">3.5%</span> y el <span class="number">6%</span> del costo financiero total. Importante, pero menos que dramático. El verdadero costo no aparece en los titulares: es la pérdida sostenida de margen fiscal frente al rescate permanente de Pemex y a un déficit estructural cuya consolidación se aplaza año tras año. La nota crediticia es el síntoma; el cuerpo enfermo es la matriz fiscal mexicana de 2024 en adelante.</p>
</div>

<p>Para los inversionistas, la lectura útil es que México sigue siendo crédito de grado de inversión y probablemente lo seguirá siendo en el horizonte de pronóstico inmediato, aunque con costos crecientes. Para los analistas de política pública, la lectura útil es que el debate fiscal debería desplazarse del ruido de las calificadoras hacia la conversación sustantiva: el costo financiero de la deuda ya supera el gasto en Bienestar más Educación combinados. Esa frase debería repetirse hasta el cansancio en cualquier discusión seria sobre presupuesto público en México.</p>

<p style="font-style: italic; color: var(--gray); margin-top: 48px; font-size: 16px;">Lo demás es ruido.</p>

<section class="refs">
  <h3>Referencias y fuentes</h3>
  <ol>
    <li><em>Moody's Ratings rebaja calificación crediticia de México de Baa2 a Baa3, cambia perspectiva de negativa a estable.</em> SHCP, comunicado del 20 de mayo de 2026; cobertura en El Universal, AM, Excélsior, Infobae.</li>
    <li><em>México juega con fuego en su calificación crediticia.</em> El Financiero, 19 de mayo de 2026.</li>
    <li><em>Tras rebaja de S&amp;P, Moody's recortaría calificación de México en 2026: Banamex.</em> Investing.com, mayo de 2026.</li>
    <li><em>Fitch ratifica calificación de México en BBB− con perspectiva estable.</em> Comunicado SHCP No. 27, 10 de abril de 2026.</li>
    <li><em>El costo financiero de la deuda pública en México crece 5.1% en 2024 y alcanzará su nivel más alto en 25 años.</em> SHCP, citado en El Imparcial, 3 de febrero de 2025.</li>
    <li><em>Se pagan por intereses de la deuda 3 mil 516 mdp diarios.</em> La Jornada, 15 de noviembre de 2025.</li>
    <li><em>Informe sobre Finanzas Públicas y Deuda Pública 4T 2024.</em> SHCP.</li>
    <li><em>Comunicado SHCP sobre acción de Moody's del 20 de mayo de 2026.</em></li>
    <li><em>Moody's recorta calificación crediticia de la deuda soberana de México.</em> El Universal, 20 de mayo de 2026.</li>
    <li><em>Deuda y presiones fiscales en los CGPE 2026.</em> CIEP, 2025.</li>
    <li><em>Riesgo país en América Latina al cierre de febrero 2026.</em> Revista Mercado / JPMorgan EMBI, marzo de 2026.</li>
    <li><em>Ley Federal de Presupuesto y Responsabilidad Hacendaria</em>, última reforma DOF 08-08-2025.</li>
    <li><em>Pre-Criterios Generales de Política Económica 2025.</em> Análisis del IMCO.</li>
  </ol>
  <p style="margin-top: 24px; font-size: 12px; font-style: italic;">Las descomposiciones de sobrecosto de las Figuras 3 y 4 son estimaciones del autor basadas en las fuentes anteriores. Comentarios y correcciones son bienvenidos.</p>
</section>

</article>
</div>
{{< /rawhtml >}}
