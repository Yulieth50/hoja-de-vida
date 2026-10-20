<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Heilys Yulieth Mosquera Urrutia | Desarrolladora Full-Stack</title>
<style>
  :root {
    --bg: #fbfaf7;
    --paper: #ffffff;
    --ink: #1c2622;
    --muted: #5f6b65;
    --line: #e4e0d5;
    --green: #12382c;
    --gold: #b08d3c;
    color-scheme: light;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #0d1713;
      --paper: #13211b;
      --ink: #ece8dc;
      --muted: #a3afa8;
      --line: #2a3a32;
      --green: #0a1f18;
      --gold: #d4b062;
      color-scheme: dark;
    }
  }
  * { box-sizing: border-box; }
  body {
    margin: 0;
    background: var(--bg);
    color: var(--ink);
    font-family: "Palatino Linotype", Palatino, "Book Antiqua", Georgia, serif;
    line-height: 1.75;
    text-align: center;
  }
  a { color: inherit; text-decoration: none; border-bottom: 1px solid var(--gold); }
  a:focus-visible { outline: 3px solid var(--gold); outline-offset: 3px; }

  .sheet { max-width: 820px; margin: 0 auto; background: var(--paper); box-shadow: 0 0 0 1px var(--line); }

  header {
    background: var(--green);
    color: #f4efe1;
    padding: 3.5rem 1.5rem 3rem;
    border-bottom: 4px solid var(--gold);
  }
  .photo {
    width: 168px; height: 168px;
    border-radius: 50%;
    object-fit: cover;
    border: 4px solid var(--gold);
    padding: 4px;
    background: var(--green);
    display: block;
    margin: 0 auto 1.4rem;
  }
  h1 {
    margin: 0;
    font-size: clamp(1.7rem, 5vw, 2.6rem);
    font-weight: 400;
    letter-spacing: .06em;
    line-height: 1.2;
  }
  .role {
    margin: .7rem 0 0;
    font-style: italic;
    font-size: 1.1rem;
    color: var(--gold);
  }
  .contact {
    margin: 1.6rem auto 0;
    max-width: 620px;
    font-size: .95rem;
    font-family: "Segoe UI", system-ui, Arial, sans-serif;
    display: flex; flex-wrap: wrap; justify-content: center; gap: .4rem 1.4rem;
  }
  .contact a { border-bottom-color: rgba(244,239,225,.4); }

  main { padding: 1rem 2rem 3rem; }
  section { padding: 2.2rem 0; border-bottom: 1px solid var(--line); }
  section:last-child { border-bottom: 0; }

  h2 {
    margin: 0 0 1.3rem;
    font-size: 1.05rem;
    font-weight: 400;
    letter-spacing: .28em;
    text-transform: uppercase;
    color: var(--green);
  }
  @media (prefers-color-scheme: dark) { h2 { color: var(--gold); } }
  h2::after {
    content: "";
    display: block;
    width: 48px; height: 2px;
    background: var(--gold);
    margin: .8rem auto 0;
  }

  p { max-width: 62ch; margin: 0 auto 1rem; }
  h3 { margin: 0; font-size: 1.15rem; font-weight: 700; }
  .meta { color: var(--muted); font-style: italic; margin: .2rem 0 1.2rem; }
  .duty { max-width: 60ch; margin: 0 auto 1rem; }
  .duty + .duty { padding-top: 1rem; border-top: 1px dotted var(--line); }

  .edu-item { margin-bottom: 1.3rem; }
  .edu-item:last-child { margin-bottom: 0; }
  .edu-item p { margin: .1rem auto 0; color: var(--muted); }

  .skill-group { margin-bottom: 1.4rem; }
  .skill-group:last-child { margin-bottom: 0; }
  .skill-group h3 { font-size: 1rem; margin-bottom: .6rem; color: var(--muted); font-weight: 400; font-style: italic; }
  .tags { display: flex; flex-wrap: wrap; gap: .5rem; justify-content: center; }
  .tag {
    font-family: "Segoe UI", system-ui, Arial, sans-serif;
    font-size: .85rem;
    padding: .25rem .9rem;
    border: 1px solid var(--gold);
    border-radius: 999px;
    color: var(--ink);
  }

  footer { padding: 1.5rem; font-size: .85rem; color: var(--muted); border-top: 4px solid var(--gold); background: var(--bg); }

  @media (max-width: 520px) { main { padding: 1rem 1.25rem 2.5rem; } }
  @media print {
    body { background: #fff; }
    .sheet { box-shadow: none; }
    header { -webkit-print-color-adjust: exact; print-color-adjust: exact; }
  }
</style>
</head>
<body>
<div class="sheet">

<header>
  <img class="photo" alt="Foto de Heilys Yulieth Mosquera Urrutia" src="foto.jpg">
  <h1>Heilys Yulieth Mosquera Urrutia</h1>
  <p class="role">Desarrolladora Full-Stack &amp; Consultora de Software</p>
  <div class="contact">
    <span>Medellín, Colombia</span>
    <a href="mailto:mosquerayulieth456@gmail.com">mosquerayulieth456@gmail.com</a>
    <a href="tel:+573235110389">+57 323 5110389</a>
    <a href="https://www.linkedin.com/in/[tu-usuario]">LinkedIn</a>
    <a href="https://github.com/[tu-usuario]">GitHub</a>
  </div>
</header>

<main>
  <section id="perfil">
    <h2>Perfil profesional</h2>
    <p>Desarrolladora de software y consultora con experiencia en el diseño de interfaces, prototipado visual en Figma, maquetación web con HTML, desarrollo de lógica de backend y automatización de procesos. Estudiante de Tecnología en Análisis y Desarrollo de Software (ADSO) en el SENA, con sólida trayectoria como desarrolladora independiente.</p>
    <p>Especializada en Python, JavaScript, TypeScript, Figma, HTML y MySQL Workbench, así como en la integración de flujos de automatización con n8n e inteligencia artificial (Ollama). Destacada por su rigor en la calidad del código, la escalabilidad, el modelado de bases de datos y la aplicación de metodologías ágiles.</p>
  </section>

  <section id="experiencia">
    <h2>Experiencia laboral</h2>
    <h3>Desarrolladora Full-Stack Independiente &amp; Consultora de Software</h3>
    <p class="meta">Independiente · Medellín, Colombia</p>
    <p class="duty">Arquitecturé, diseñé interfaces en Figma y maqueté en HTML soluciones web escalables orientadas al control de inventarios y gestión operativa para clientes.</p>
    <p class="duty">Implementé flujos de backend robustos, consultas avanzadas en bases de datos relacionales y lógica de software para la administración eficiente de existencias.</p>
    <p class="duty">Integré herramientas de automatización de flujos de trabajo (<strong>n8n</strong>) y modelos de inteligencia artificial (<strong>Ollama</strong>) para optimizar y potenciar la operatividad empresarial.</p>
    <p class="duty">Apliqué metodologías ágiles (<strong>Scrum</strong>) y buenas prácticas de control de versiones con Git y GitHub para garantizar el cumplimiento de entregables y la mantenibilidad del código.</p>
  </section>

  <section id="educacion">
    <h2>Educación</h2>
    <div class="edu-item">
      <h3>Tecnología en Análisis y Desarrollo de Software (ADSO)</h3>
      <p>Servicio Nacional de Aprendizaje (SENA) · En curso</p>
    </div>
    <div class="edu-item">
      <h3>Técnico en Programación de Software</h3>
      <p>Servicio Nacional de Aprendizaje (SENA) · Graduada (2025)</p>
    </div>
    <div class="edu-item">
      <h3>Bachillerato Académico</h3>
      <p>I.E. Héctor Abad Gómez · Graduada (2025)</p>
    </div>
  </section>

  <section id="habilidades">
    <h2>Habilidades técnicas</h2>
    <div class="skill-group">
      <h3>Diseño y Frontend</h3>
      <div class="tags"><span class="tag">Figma</span><span class="tag">HTML5</span><span class="tag">CSS3</span><span class="tag">JavaScript</span><span class="tag">TypeScript</span></div>
    </div>
    <div class="skill-group">
      <h3>Lenguajes y Backend</h3>
      <div class="tags"><span class="tag">Python</span><span class="tag">Django</span><span class="tag">FastAPI</span></div>
    </div>
    <div class="skill-group">
      <h3>Bases de datos</h3>
      <div class="tags"><span class="tag">MySQL</span></div>
    </div>
  </section>
</main>

<footer>Heilys Yulieth Mosquera Urrutia · Medellín, Colombia</footer>

</div>
</body>
</html>
