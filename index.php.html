<?php session_start(); ?>
<!DOCTYPE html>
<html lang="sw">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CHAP CHAP - Duka La Mtandaoni</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(to bottom right, #f9f9f9, #e6f2ff);
      color: #333;
    }
    header, footer {
      background: #0d47a1;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav ul {
      list-style: none;
      padding: 0;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
    }
    .category {
      margin-bottom: 3rem;
    }
    .product {
      background: white;
      border: 1px solid #ccc;
      padding: 1rem;
      margin: 1rem 0;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      display: flex;
      gap: 1rem;
      align-items: center;
    }
    .product img {
      width: 100px;
      height: 100px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product-info {
      flex: 1;
    }
    .product h3 {
      margin: 0 0 0.5rem 0;
    }
    .product button {
      background: #0288d1;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    form input, form select {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.25rem;
      margin-bottom: 1rem;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    form button {
      background: #00695c;
      color: white;
      border: none;
      padding: 0.75rem;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }
    .upload-section {
      margin-top: 2rem;
      padding: 1rem;
      background: #ffffff;
      border: 1px solid #ccc;
      border-radius: 10px;
    }
    .upload-section h3 {
      margin-top: 0;
    }
    .auth-section {
      margin: 2rem 0;
      padding: 1rem;
      background: #f0f8ff;
      border: 1px solid #bbb;
      border-radius: 10px;
    }
    .auth-section form {
      max-width: 400px;
      margin: auto;
    }
  </style>
</head>
<body>
  <header>
    <h1>CHAP CHAP</h1>
    <nav>
      <ul>
        <li><a href="#nyumbani">Nyumbani</a></li>
        <li><a href="#bidhaa">Bidhaa</a></li>
        <li><a href="#malipo">Malipo</a></li>
        <li><a href="#wasiliana">Wasiliana Nasi</a></li>
        <li><a href="#akaunti">Akaunti</a></li>
      </ul>
    </nav>
  </header>

  <?php if (isset($_SESSION['user'])): ?>
    <p style="text-align:center;">Karibu, <strong><?php echo $_SESSION['user']; ?></strong>! <a href="logout.php">[Toka]</a></p>
  <?php endif; ?>

  <section id="nyumbani">
    <h2>Karibu CHAP CHAP</h2>
    <p>Tunauza bidhaa mbalimbali kwa matumizi ya nyumbani, ofisini, mashuleni na zaidi. Nunua kwa urahisi na fanya malipo papo hapo!</p>
  </section>

  <section id="bidhaa">
    <h2>Bidhaa Zetu</h2>
    <div class="category">
      <h3>🍎 Bidhaa za Vyakula na Vinywaji</h3>
      <div class="product">
        <img src="images/mchele.jpg" alt="Mchele">
        <div class="product-info">
          <h3>Mchele</h3>
          <p>1 kg - TZS 2,000 – 3,500</p>
          <button>Weka Oda</button>
        </div>
      </div>
    </div>
  </section>

  <?php if (isset($_SESSION['user'])): ?>
    <section class="upload-section">
      <h3>Ongeza Bidhaa Mpya</h3>
      <form action="upload.php" method="POST" enctype="multipart/form-data">
        <label>Jina la Bidhaa:</label>
        <input type="text" name="jina_bidhaa" required>

        <label>Bei:</label>
        <input type="text" name="bei" required>

        <label>Picha ya Bidhaa:</label>
        <input type="file" name="picha_bidhaa" accept="image/*" required>

        <button type="submit">Ongeza Bidhaa</button>
      </form>
    </section>
  <?php else: ?>
    <section class="upload-section">
      <p><strong>Tafadhali ingia kwenye akaunti yako ili uweze kuongeza bidhaa.</strong></p>
    </section>
  <?php endif; ?>

  <section id="malipo">
    <h2>Fanya Malipo</h2>
    <form action="https://payment-gateway.example.com/process" method="POST">
      <label>Jina Kamili:</label>
      <input type="text" name="jina" required>

      <label>Aina ya Malipo:</label>
      <select name="aina_malipo">
        <option value="mpesa">M-Pesa</option>
        <option value="tigopesa">Tigo Pesa</option>
        <option value="airtelmoney">Airtel Money</option>
        <option value="kadi">Kadi ya Benki</option>
      </select>

      <label>Jumla ya Malipo:</label>
      <input type="number" name="kiasi" required>

      <button type="submit">Lipa Sasa</button>
    </form>
  </section>

  <section id="akaunti" class="auth-section">
    <h2>Ingia / Jisajili</h2>
    <form action="login.php" method="POST">
      <label>Barua Pepe:</label>
      <input type="email" name="email" required>

      <label>Nenosiri:</label>
      <input type="password" name="password" required>

      <button type="submit">Ingia</button>
    </form>
    <p>Huna akaunti? <a href="register.php">Jisajili hapa</a></p>
  </section>

  <section id="wasiliana">
    <h2>Wasiliana Nasi</h2>
    <p>Simu: +255 712 345 678</p>
    <p>Barua pepe: info@chapchap.co.tz</p>
  </section>

  <footer>
    <p>&copy; 2025 CHAP CHAP - Haki zote zimehifadhiwa.</p>
  </footer>
</body>
</html>
