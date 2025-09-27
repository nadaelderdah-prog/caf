<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CAF CORMANO</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0; padding: 0;
      background-color: #fdfdfd;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #004080, #0066cc);
      color: white;
      text-align: center;
      padding: 50px 20px;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      margin-top: 10px;
      font-size: 1.2em;
    }
    nav {
      background: #003366;
      text-align: center;
      padding: 15px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffdd00;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 40px 20px;
    }
    h2 {
      color: #004080;
      margin-bottom: 15px;
    }
    .services ul {
      list-style: none;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 10px;
    }
    .services li {
      background: #e6f0ff;
      padding: 15px;
      border-radius: 8px;
      text-align: center;
      font-weight: bold;
    }
    .contact {
      background: #004080;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    .contact a {
      color: #ffdd00;
      text-decoration: none;
      font-weight: bold;
    }
    .btn-whatsapp {
      display: inline-block;
      background: #25D366;
      color: white !important;
      padding: 12px 20px;
      border-radius: 25px;
      margin-top: 15px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }
    .btn-whatsapp:hover {
      background: #1ebe5d;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    <h1>CAF CORMANO</h1>
    <p>Assistenza fiscale completa e professionalità</p>
  </header>

  <nav>
    <a href="#servizi">Servizi</a>
    <a href="#orari">Orari</a>
    <a href="#contatti">Contatti</a>
  </nav>

  <div class="container">
    <section id="descrizione">
      <h2>Chi Siamo</h2>
      <p>Offriamo assistenza fiscale completa e professionalità. 
      Affidati a noi per le tue pratiche fiscali in tutta sicurezza.</p>
    </section>

    <section id="servizi" class="services">
      <h2>I Nostri Servizi</h2>
      <ul>
        <li>730</li>
        <li>ISEE</li>
        <li>RED</li>
        <li>IMU</li>
        <li>SUCCESSIONI</li>
        <li>BONUS SOCIALI</li>
        <li>IMMIGRAZIONE</li>
        <li>CITTADINANZA</li>
        <li>DECRETO FLUSSI</li>
      </ul>
    </section>

    <section id="orari">
      <h2>Orari di Apertura</h2>
      <p><strong>Lunedì - Venerdì:</strong> 9:00 - 13:00 / 14:00 - 18:00</p>
    </section>
  </div>

  <footer class="contact" id="contatti">
    <h2>Contatti</h2>
    <p>📍 Via Gramsci, 69, Cormano, 20032</p>
    <p>📞 <a href="tel:37512581743">375 125 81743</a></p>
    <p>📧 <a href="mailto:cafcormano@gmail.com">cafcormano@gmail.com</a></p>
    <a class="btn-whatsapp" href="https://wa.me/3937512581743" target="_blank">💬 Scrivici su WhatsApp</a>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2794.9778774860934!2d9.167!3d45.548!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4786b07b27e1d3f5%3A0x123456789abcdef!2sVia%20Gramsci%2C%2069%2C%2020032%20Cormano%20MI!5e0!3m2!1sit!2sit!4v0000000000000"></iframe>
  </footer>

</body>
</html>
