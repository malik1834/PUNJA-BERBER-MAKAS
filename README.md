
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PUNJA - Makas Çeşitleri</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');

    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fafafa;
      color: #222;
    }

    header {
      background-color: #222;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      letter-spacing: 3px;
      position: relative;
      box-shadow: 0 3px 8px rgba(0,0,0,0.25);
    }

    /* Logo with goat emoji */
    .logo {
      display: flex;
      align-items: center;
      font-size: 1.8rem;
      gap: 10px;
      user-select: none;
    }
    .logo .goat {
      font-size: 2.4rem;
    }

    /* Right side menu - message */
    nav {
      font-size: 1rem;
      color: #ddd;
      background: #333;
      padding: 10px 25px;
      border-radius: 8px;
      font-weight: 600;
      box-shadow: 0 2px 10px rgba(0,0,0,0.3);
      user-select: none;
      max-width: 350px;
      text-align: center;
    }

    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h1 {
      font-family: 'Montserrat', sans-serif;
      font-size: 2.5rem;
      margin-bottom: 25px;
      color: #ff3b3b;
      text-align: center;
      letter-spacing: 3px;
      text-shadow: 1px 1px 3px #aaa;
    }

    ul.cevher {
      list-style-type: square;
      max-width: 500px;
      margin: 0 auto;
      font-size: 1.15rem;
      line-height: 1.6;
      color: #444;
    }

    ul.cevher li {
      padding: 8px 0;
      border-bottom: 1px solid #eee;
      transition: background-color 0.3s ease;
      cursor: default;
    }

    ul.cevher li:hover {
      background-color: #ff3b3b10;
      color: #ff3b3b;
    }

    footer {
      text-align: center;
      margin: 50px 0 25px;
      font-size: 1.2rem;
      color: #555;
      user-select: none;
    }

    footer a {
      color: #ff3b3b;
      font-weight: 700;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <span class="goat">🐐</span>
      <span>PUNJA</span>
    </div>
    <nav>Makasların fiyatlarını öğrenmek isterseniz<br>müşteri hizmetlerini arayın</nav>
  </header>

  <main>
    <h1>Berber Makası Çeşitleri</h1>
    <ul class="cevher">
      <li>Paslanmaz Çelik Makas</li>
      <li>Profesyonel Berber Makası</li>
      <li>Ergonomik Tasarımlı Makas</li>
      <li>Saç Kesim Makası</li>
      <li>İnce Uçlu Makas</li>
      <li>Çift Telli Makas</li>
      <li>Sağ ve Sol El Makasları</li>
      <li>Saç Perçin Makasları</li>
    </ul>
  </main>

  <footer>
    Müşteri Hizmetleri: <a href="tel:+905326865879">0532 686 58 79</a>
  </footer>
</body>
</html>

