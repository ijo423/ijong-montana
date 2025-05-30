<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ijong Montana Travel</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f8ff;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #2c3e50;
      font-weight: bold;
    }
    .hero {
      text-align: center;
      padding: 40px 20px;
      background: #ecf0f1;
    }
    .services, .gallery {
      padding: 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .service, .gallery-item {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .gallery-item img {
      max-width: 100%;
      border-radius: 8px;
    }
    .wa-button {
      display: inline-block;
      background-color: #25D366;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 10px;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ijong Montana Travel</h1>
    <p>Solusi perjalanan nyaman dan terpercaya</p>
  </header>

  <nav>
    <a href=\"#layanan\">Layanan</a>
    <a href=\"#galeri\">Galeri</a>
    <a href=\"#kontak\">Kontak</a>
  </nav>

  <section class=\"hero\">
    <h2>Jelajahi Lombok dengan Aman dan Nyaman</h2>
    <p>Kami menyediakan layanan travel, antar jemput bandara, dan paket wisata.</p>
    <a class=\"wa-button\" href=\"https://wa.me/6287846133523\" target=\"_blank\">Hubungi via WhatsApp</a>
  </section>

  <section id=\"layanan\" class=\"services\">
    <div class=\"service\">
      <h3>Sewa Mobil</h3>
      <p>Berbagai pilihan mobil dengan sopir berpengalaman.</p>
    </div>
    <div class=\"service\">
      <h3>Antar Jemput Bandara</h3>
      <p>Layanan cepat dan tepat waktu ke/dari Bandara Lombok.</p>
    </div>
    <div class=\"service\">
      <h3>Paket Wisata</h3>
      <p>Tour ke destinasi terbaik di Lombok, aman dan menyenangkan.</p>
    </div>
  </section>

  <section id=\"galeri\" class=\"gallery\">
    <div class=\"gallery-item\">
      <img src=\"https://source.unsplash.com/featured/?beach\" alt=\"Pantai\">
      <p>Pantai Eksotis di Lombok</p>
    </div>
    <div class=\"gallery-item\">
      <img src=\"https://source.unsplash.com/featured/?mountain\" alt=\"Gunung\">
      <p>Wisata Alam Pegunungan</p>
    </div>
    <div class=\"gallery-item\">
      <img src=\"https://source.unsplash.com/featured/?waterfall\" alt=\"Air Terjun\">
      <p>Air Terjun Menakjubkan</p>
    </div>
  </section>

  <section id=\"kontak\" class=\"hero\">
    <h2>Hubungi Kami</h2>
    <p>WhatsApp: <a href=\"https://wa.me/6287846133523\" target=\"_blank\">087846133523</a></p>
    <p>Lokasi: Desa Banyu Urip, Lombok Barat</p>
  </section>

  <footer>
    <p>&copy; 2025 Ijong Montana Travel</p>
  </footer>
</body>
