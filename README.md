<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ashley Alonzo | Portafolio</title>
  <style>
    /* Variables de colores (Paleta Lila, Morado y Púrpura) */
    :root {
      --bg-gradient: linear-gradient(135deg, #1f1235 0%, #321e50 40%, #4a2875 100%);
      --card-bg: rgba(255, 255, 255, 0.96);
      --primary-purple: #6b3ba7;
      --secondary-purple: #8b5cf6;
      --soft-lilac: #e9d5ff;
      --dark-text: #2d1842;
      --muted-text: #5c4378;
      --border-color: #d8b4fe;
      --table-bg: #f8f4fc;
    }

    /* Estilos Generales y Fondo */
    body {
      margin: 0;
      padding: 40px 15px;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: var(--bg-gradient);
      background-attachment: fixed;
      color: var(--dark-text);
      line-height: 1.6;
    }

    /* Contenedor / Tarjeta Principal */
    .container {
      max-width: 850px;
      margin: 0 auto;
      background: var(--card-bg);
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }

    /* Imágenes y Banners */
    img {
      max-width: 100%;
      height: auto;
      border-radius: 12px;
    }

    .banner img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(107, 59, 167, 0.2);
    }

    /* Encabezados */
    h1 {
      color: var(--primary-purple);
      font-size: 2.3em;
      margin-top: 20px;
      margin-bottom: 5px;
    }

    h2 {
      color: var(--primary-purple);
      border-bottom: 2px solid var(--border-color);
      padding-bottom: 8px;
      margin-top: 35px;
      font-size: 1.5em;
    }

    h3 {
      color: var(--secondary-purple);
      margin-top: 10px;
    }

    p {
      color: var(--dark-text);
      font-size: 1.05em;
    }

    /* Navegación y Badges */
    .nav-tabs {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 8px;
      margin: 20px 0;
    }

    .nav-tabs a img {
      transition: transform 0.2s ease;
    }

    .nav-tabs a img:hover {
      transform: translateY(-3px);
    }

    /* Divisores */
    hr {
      border: none;
      height: 1px;
      background: linear-gradient(to right, transparent, var(--border-color), transparent);
      margin: 35px 0;
    }

    /* Tablas Estilizadas */
    table {
      width: 100%;
      border-collapse: separate;
      border-spacing: 0;
      margin: 20px 0;
      background-color: var(--table-bg);
      border-radius: 12px;
      overflow: hidden;
      border: 1px solid var(--border-color);
    }

    td {
      padding: 20px;
      vertical-align: top;
    }

    table h3 {
      margin-top: 0;
    }

    ul {
      padding-left: 20px;
      margin: 0;
    }

    li {
      margin-bottom: 6px;
    }

    /* Ajustes para móviles */
    @media (max-width: 600px) {
      .container {
        padding: 20px;
      }
      table, tr, td {
        display: block;
        width: 100% !important;
        box-sizing: border-box;
      }
      td {
        border-bottom: 1px dashed var(--border-color);
      }
      td:last-child {
        border-bottom: none;
      }
    }
  </style>
</head>
<body>

<div class="container">

  <!-- BANNER -->
  <p align="center" class="banner">
    <img src="https://github.com/ashley02alon/image/blob/746ed52eaa55fc2fdfc68e85c105ce7081250d86/ChatGPT%20Image%207%20oct%202026%2C%2011_09_30.png" alt="Banner de perfil">
  </p>

  <!-- HEADER -->
  <h1 align="center">Ashley Alonzo</h1>

  <p align="center">
    <i>Student • Creative Thinker • Community-Oriented</i>
  </p>

  <p align="center">
    🌷 Kindness &nbsp; • &nbsp; 🤝 Collaboration &nbsp; • &nbsp; 💜 Service
  </p>

  <br>

  <!-- NAVIGATION TABS -->
  <p align="center" class="nav-tabs">
    <a href="#about-me">
      <img src="https://img.shields.io/badge/🌸%20About%20Me-C9B6E4?style=for-the-badge&labelColor=5c4378" alt="About Me" />
    </a>
    <a href="#professional">
      <img src="https://img.shields.io/badge/💻%20Professional-B8A4D0?style=for-the-badge&labelColor=5c4378" alt="Professional" />
    </a>
    <a href="#certifications">
      <img src="https://img.shields.io/badge/🏆%20Certifications-A98BC2?style=for-the-badge&labelColor=5c4378" alt="Certifications" />
    </a>
    <a href="#community">
      <img src="https://img.shields.io/badge/💜%20Community-967BB6?style=for-the-badge&labelColor=5c4378" alt="Community" />
    </a>
    <a href="#personal">
      <img src="https://img.shields.io/badge/🌷%20Personal-D8B9E2?style=for-the-badge&labelColor=5c4378" alt="Personal" />
    </a>
  </p>

  <hr>

  <!-- ABOUT ME -->
  <h2 id="about-me">🌸 About Me</h2>

  <p>
    I don't believe success is measured by how much attention we receive.
    I believe it's reflected in how we treat people, how we collaborate,
    and the positive environment we create around us.
  </p>

  <p>
    Kindness, collaboration and service are the values that guide everything I do.
    I believe that <b>listening carefully is the first step toward creating meaningful solutions.</b>
  </p>

  <hr>

  <!-- PROFESSIONAL -->
  <h2 id="professional">💻 Professional</h2>

  <table>
    <tr>
      <td width="50%">
        <h3>📊 Skills</h3>
        <ul>
          <li>Microsoft Excel</li>
          <li>Presentations</li>
          <li>Organization</li>
          <li>Communication</li>
        </ul>
      </td>

      <td width="50%">
        <h3>🤝 Soft Skills</h3>
        <ul>
          <li>Teamwork</li>
          <li>Empathy</li>
          <li>Collaboration</li>
          <li>Active Listening</li>
        </ul>
      </td>
    </tr>
  </table>

  <hr>

  <!-- CERTIFICATIONS -->
  <h2 id="certifications">🏆 Certifications</h2>

  <p align="center">
    <i>Continuous learning and professional growth</i>
  </p>

  <table>
    <tr>
      <td align="center" width="33%">
        <h3 style="font-size: 2em; margin-bottom: 5px;">📊</h3>
        <b>Microsoft Excel</b><br>
        <span style="color: var(--muted-text);">Certified</span>
      </td>

      <td align="center" width="33%">
        <h3 style="font-size: 2em; margin-bottom: 5px;">📈</h3>
        <b>Excel Expert</b><br>
        <span style="color: var(--muted-text);">Certified</span>
      </td>

      <td align="center" width="33%">
        <h3 style="font-size: 2em; margin-bottom: 5px;">🐍</h3>
        <b>Python Essentials 1</b><br>
        <span style="color: var(--muted-text);">Certified</span>
      </td>
    </tr>
  </table>

  <hr>

  <!-- COMMUNITY -->
  <h2 id="community">💜 Community</h2>

  <h3>🏠 TECHO Panamá</h3>
  <p>An experience that strengthened my understanding of <b>teamwork, service and community</b>.</p>

  <h3>🧸 Children's Ministry</h3>
  <p>A space where I develop <b>empathy, responsibility and communication</b> while supporting others.</p>

  <hr>

  <!-- PERSONAL -->
  <h2 id="personal">🌷 Personal</h2>

  <table>
    <tr>
      <td align="center">🎵<br><b>Music</b></td>
      <td align="center">🧶<br><b>Crochet</b></td>
      <td align="center">🎨<br><b>Creativity</b></td>
      <td align="center">🌺<br><b>Tembleques</b></td>
    </tr>
  </table>

  <hr>

  <!-- FOOTER SECTION -->
  <h2 align="center" style="border: none;">🌱 What I've Learned</h2>

  <p align="center">
    <i>
      These experiences strengthened my belief that helping others
      is one of the most meaningful ways to grow.
    </i>
  </p>

  <br>

  <p align="center" style="color: var(--secondary-purple); font-size: 1.2em;">
    ✦ ───────────── 💜 ───────────── ✦
  </p>

  <p align="center" style="font-size: 1.1em;">
    <b>Thank you for visiting my portfolio!</b> ✨
  </p>

</div>

</body>
</html>
