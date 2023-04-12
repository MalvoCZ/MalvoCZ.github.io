<!DOCTYPE html>
<html>
<head>
  <title>Franta Omáčka</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
    }
    .header {
      padding: 20px;
      text-align: center;
    }
    .nav {
      display: flex;
      justify-content: center;
      background-color: gold;
      padding: 10px;
    }
    .nav a {
      color: black;
      padding: 8px 16px;
      text-decoration: none;
      margin: 0 10px;
    }
    .nav a:hover {
      background-color: black;
      color: gold;
    }
    .content {
      padding: 20px;
    }
    .footer {
      background-color: gold;
      padding: 10px;
      text-align: center;
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
    }
    .image-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .image-container img {
      max-width: 100%;
      max-height: 100%;
      object-fit: contain;
    }
  </style>
  <script>
    // Funkce pro změnu obrázku každých 5 sekund
    function changeImage() {
      var images = ["image1.jpg", "image2.jpg", "image3.jpg"]; // seznam obrázků
      var currentIndex = 0; // aktuální index obrázku

      setInterval(function() {
        document.getElementById("image").src = images[currentIndex]; // změna zobrazovaného obrázku
        currentIndex = (currentIndex + 1) % images.length; // inkrementace indexu a zajištění zacyklení
      }, 5000); // interval 5 sekund
    }
  </script>
</head>
<body onload="changeImage()">
  <div class="header">
    <h1>Informace o sobě</h1>
  </div>
  <div class="nav">
    <a href="#about">O mně</a>
    <a href="#location">Bydliště</a>
    <a href="#interests">Zájmy</a>
    <a href="#links">Odkazy</a>
    <a href="#contacts">Kontakty</a>
  </div>
  <div class="content" id="about">
    <h2>Informace o mně</h2>
    <p>Jsem Franta Omáčka, vymyšlená postava s různými dobrodružstvími. Můj život je plný neuvěřitelných příběhů a zážitků. Rád se bavím, poznávám nové lidi a objevuji nová místa.</p>
  </div>
  <div class="content" id="location">
    <h2>Informace o místě bydliště</h2>
    <p>Mým domovem je krásné město Mělník, které se nachází v České republice. Mělník je historické město ležící na soutoku dvou řek, Labe a Vltavy. Je známé pro své nádherné zámky, památky a výborné víno z místních vinic.

  </div>
  <div class="content" id="interests">
    <h2>Zájmy</h2>
    <p>Mými zájmy jsou dobrodružství, cestování, objevování nových kultur a tradic, sportování, hraní na hudební nástroje a čtení knih. Rád se zapojuji do různých aktivit a poznávám nové věci.</p>
  </div>
  <div class="content" id="links">
    <h2>Odkazy</h2>
    <ul>
      <li><a href="https://www.example.com">Můj blog</a></li>
      <li><a href="https://www.example.com/social-media">Můj Instagram</a></li>
      <li><a href="https://www.example.com/portfolio">Můj portfolio</a></li>
    </ul>
  </div>
  <div class="content" id="contacts">
    <h2>Kontakty</h2>
    <p>Můžete mě kontaktovat na následujících kontaktních údajích:</p>
    <ul>
      <li>Email: franta.omacka@example.com</li>
      <li>Telefon: +420 123 456 789</li>
      <li>Adresa: Ulice 123, Mělník, 12345</li>
    </ul>
  </div>
  <div class="footer">
    <p>Vytvořeno Frantou Omáčkou, 2023</p>
  </div>
</body>
</html>
