<html>
<head>
  <title>Franta Omáčka - Osobní web</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
    }
    .header {
      text-align: center;
      padding: 20px;
    }
    .nav {
      display: flex;
      justify-content: center;
      margin-top: 20px;
    }
    .nav a {
      padding: 10px;
      color: white;
      text-decoration: none;
      margin: 0 10px;
      border: 1px solid white;
      border-radius: 5px;
    }
    .nav a:hover {
      background-color: white;
      color: black;
    }
    .content {
      margin-top: 30px;
      padding: 0 20px;
    }
    .footer {
      text-align: center;
      padding: 20px;
      position: fixed;
      bottom: 0;
      left: 0;
      right: 0;
      background-color: black;
    }
    .footer a {
      color: white;
      text-decoration: none;
    }
    .footer a:hover {
      color: gold;
    }
    .image {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
    }
  </style>
  <script>
    var images = [
      "581D490E-74C6-4A99-94B9-5FB473F0DF7B.jpeg",
      "7511EF35-1D68-4C25-9FEA-A0E1ACC35929.jpeg",
      "8937CD4A-3536-4B49-BB95-79B06A7F44B2.jpeg"
    ];
    var currentIndex = 0;
    setInterval(changeImage, 5000);

    function changeImage() {
      var image = document.getElementById("header-image");
      currentIndex = (currentIndex + 1) % images.length;
      image.src = images[currentIndex];
    }
  </script>
</head>
<body>
  <div class="header">
    <h1>Vítejte na mém osobním webu</h1>
    <img id="header-image" class="image" src="581D490E-74C6-4A99-94B9-5FB473F0DF7B.jpeg">
  </div>
  <div class="nav">
    <a href="#about">Informace o sobě</a>
    <a href="#location">Informace o místě bydliště</a>
    <a href="#interests">Moje zájmy</a>
    <a href="#links">Odkazy</a>
    <a href="#contacts">Kontakty</a>
  </div>
  <div class="content">
    <h2 id="about">Informace o sobě</h2>
    <p>Jsem Franta Omáčka, vymyšlená postava s bohatým životním příběhem. Rád cestuji po světě a objevuji nová místa. Baví mě sport, zejména fotbal a plavání. Miluji kreativitu a rád tvořím vlastní obsah, jako jsou malby a sochy. Jsem také nadšený kuchař a rád experimentuji s novými recepty.</p>
    <h2 id="location">Informace o místě bydliště</h2>
    <p>Jsem hrdý obyvatel Prahy, krásného historického města s bohatou kulturou a zajímavou historií. V Praze rád trávím čas procházkami po Starém Městě a objevováním skrytých uliček.</p>
    <h2 id="interests">Moje zájmy</h2>
    <p>Mými hlavními zájmy jsou cestování, sport, umění a kulinářství. Rád zkoumám nové destinace a poznávám různé kultury. Sport mě udržuje ve formě a nabíjí energií. Rád navštěvuji galerie a muzea a obdivuji různé formy umění. Kuchaření je pro mě způsob relaxace a kreativity.</p>
    <h2 id="links">Odkazy</h2>
    <ul>
      <li><a href="http://www.example.com" target="_blank">www.example.com</a> - Ukázkový odkaz 1</li>
      <li><a href="http://www.samplelink.com" target="_blank">www.samplelink.com</a> - Ukázkový odkaz 2</li>
      <li><a href="http://www.demo.com" target="_blank">www.demo.com</a> - Ukázkový odkaz 3</li>
    </ul>
    <h2 id="contacts">Kontakty</h2>
    <p>Můžete mě kontaktovat na následujících adresách:</p>
    <ul>
      <li>Email: franta.omacka@example.com</li>
      <li>Telefon: +420 123 456 789</li>
    </ul>
  </div>
  <div class="footer">
    <p>&copy; 2023 Franta Omáčka. Všechna práva vyhrazena. | Obrázky: 581D490E-74C6-4A99-94B9-5FB473F0DF7B.jpeg, 7511EF35-1D68-4C25-9FEA-A0E1ACC35929.jpeg, 8937CD4A-3536-4B49-BB95-79B06A7F44B2.jpeg</p>
  </div>
</body>
</html>

