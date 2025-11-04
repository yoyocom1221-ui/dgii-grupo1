[Uploading pagina_web_landing_single_f<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Dirección General de Impuestos Internos (DGII)</title>
  <style>
    body {
      margin: 0;
      font-family: 'Inter', system-ui, sans-serif;
      background: linear-gradient(to bottom, white, #f0fdf4);
      color: #1f2937;
    }
    header, footer {
      max-width: 1200px;
      margin: auto;
      padding: 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 { font-size: 1.25rem; margin: 0; }
    header p { font-size: 0.8rem; color: #6b7280; margin: 0; }
    nav a {
      margin-left: 1rem;
      text-decoration: none;
      color: #1f2937;
    }
    nav a:hover { color: #1d4ed8; }
    main { max-width: 1200px; margin: auto; padding: 1rem; text-align: center; }
    h2 { color: #15803d; font-size: 2.5rem; }
    section { margin: 3rem 0; }
    button, a.btn {
      background: #15803d;
      color: white;
      padding: 0.75rem 1.5rem;
      border: none;
      border-radius: 0.5rem;
      cursor: pointer;
    }
    button:hover, a.btn:hover { opacity: 0.9; }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 10px;
      margin-top: 1rem;
    }
    .gallery img {
      width: 100%;
      height: 100px;
      object-fit: cover;
      border-radius: 0.5rem;
      cursor: pointer;
      transition: transform 0.2s;
    }
    .gallery img:hover { transform: scale(1.05); }
    form {
      max-width: 600px;
      margin: auto;
      display: grid;
      gap: 10px;
    }
    input, textarea {
      padding: 0.75rem;
      border-radius: 0.5rem;
      border: 1px solid #d1d5db;
    }
    footer {
      border-top: 1px solid #e5e7eb;
      font-size: 0.875rem;
      color: #6b7280;
    }
    .fade-in-up {
      animation: fadeUp 0.6s ease both;
    }
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(8px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
  <script>
    function copyLink() {
      const link = window.location.href;
      navigator.clipboard.writeText(link).then(() => {
        alert('Enlace copiado al portapapeles.');
      }).catch(() => {
        alert('Copia el enlace manualmente desde la barra del navegador.');
      });
    }
  </script>
</head>
<body>
  <header>
    <div style="display:flex; align-items:center; gap:10px;">
      <div style="background:#15803d; color:white; padding:0.75rem; border-radius:1rem; font-weight:bold;">DGII</div>
      <div>
        <h1>Dirección General de Impuestos Internos (DGII)</h1>
        <p>República Dominicana</p>
      </div>
    </div>
    <nav>
      <a href="#info">Información</a>
      <a href="#grupo">Grupo 1</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <section>
      <h2 class="fade-in-up">Bienvenidos a la Dirección General de Impuestos Internos (DGII)</h2>
      <p>Esta página fue creada como parte de una actividad educativa. Su propósito es brindar información general sobre la DGII y reconocer la participación del Grupo 1 en la elaboración de este proyecto.</p>
      <div class="gallery">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/85/Emblem_of_the_Dominican_Republic.svg" alt="Escudo de la República Dominicana">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/12/Flag_of_the_Dominican_Republic.svg" alt="Bandera de la República Dominicana">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Coat_of_arms_of_the_Dominican_Republic.svg" alt="Emblema nacional">
      </div>
    </section>

    <section id="info">
      <h3>Sobre la DGII</h3>
      <p>La <strong>Dirección General de Impuestos Internos (DGII)</strong> es la institución del Estado dominicano responsable de administrar, recaudar y fiscalizar los impuestos internos del país. Su misión principal es garantizar el cumplimiento de las obligaciones tributarias, fomentar la transparencia y contribuir al desarrollo económico mediante una gestión moderna y eficiente.</p>
    </section>

    <section id="grupo">
      <h3>Proyecto elaborado por el Grupo 1</h3>
      <p>Este trabajo fue desarrollado como parte de una actividad educativa y busca demostrar buenas prácticas en desarrollo web accesible e interactivo. Integrantes:</p>
      <ul style="list-style:none; padding:0;">
        <li>• Shantal (#2)</li>
        <li>• Julio Ángel Asencio (#5)</li>
        <li>• Francis Ezequiel Familia (#11)</li>
        <li>• Alexanyer Maldonado (#14)</li>
        <li>• Brian Yair (#23)</li>
        <li>• Yadel Valentín (#28)</li>
      </ul>
      <button onclick="copyLink()">Copiar enlace de esta página</button>
    </section>

    <section id="contacto">
      <h3>Contacto</h3>
      <p>Si deseas comunicarte con la Dirección General de Impuestos Internos, completa el siguiente formulario. (Configurado con Formspree).</p>
      <form action="https://formspree.io/f/{YOUR_FORM_ID}" method="POST">
        <input type="text" name="name" placeholder="Nombre" required>
        <input type="email" name="email" placeholder="Correo electrónico" required>
        <textarea name="message" rows="5" placeholder="Tu mensaje"></textarea>
        <button type="submit">Enviar mensaje</button>
      </form>
    </section>
  </main>

  <footer>
    <div>© 2025 Dirección General de Impuestos Internos (DGII). Todos los derechos reservados.</div>
    <div>
      <a href="#" style="margin-right:10px; color:#15803d;">Política de privacidad</a>
      <a href="#" style="color:#15803d;">Términos de uso</a>
    </div>
  </footer>
</body>
</html>
ile.jsx…]()
