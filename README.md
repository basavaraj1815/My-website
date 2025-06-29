<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>बिजनेस वेबसाइट</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background-color: #f4f4f4;
      color: #333;
    }
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }
    header {
      background-color: #007B5E;
      color: #fff;
      padding: 20px 0;
    }
    header h1 {
      text-align: center;
    }
    nav {
      text-align: center;
      margin-top: 10px;
    }
    nav a {
      margin: 0 15px;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 0;
      background: #fff;
      margin-bottom: 10px;
    }
    section h2 {
      margin-bottom: 20px;
      text-align: center;
      color: #007B5E;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      padding: 10px 0;
      text-align: center;
    }
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
    @media (max-width: 768px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
      .container {
        padding: 10px;
      }
    }
  </style>
  <script>
    console.log("Page loaded: बिजनेस वेबसाइट");
  </script>
</head>
<body onload="console.log('Body loaded')">
  <header>
    <div class="container">
      <h1>मेरी कंपनी</h1>
      <nav>
        <a href="#home" onclick="console.log('Navigated to Home')">Home</a>
        <a href="#services" onclick="console.log('Navigated to Services')">Services</a>
        <a href="#about" onclick="console.log('Navigated to About')">About</a>
        <a href="#contact" onclick="console.log('Navigated to Contact')">Contact</a>
      </nav>
    </div>
  </header>

  <section id="home">
    <div class="container">
      <h2>Welcome to Our Business</h2>
      <p style="text-align:center">हम आपके बिजनेस को नई ऊँचाइयों तक पहुंचाने में मदद करते हैं।</p>
    </div>
  </section>

  <section id="services">
    <div class="container">
      <h2>हमारी सेवाएं</h2>
      <ul>
        <li>वेबसाइट डेवेलपमेंट</li>
        <li>डिजिटल मार्केटिंग</li>
        <li>SEO सेवाएं</li>
      </ul>
    </div>
  </section>

  <section id="about">
    <div class="container">
      <h2>हमारे बारे में</h2>
      <p style="text-align:center">हम एक अनुभवी और भरोसेमंद टीम हैं जो व्यवसायों को ऑनलाइन पहचान दिलाने में विशेषज्ञता रखते हैं।</p>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>संपर्क करें</h2>
      <p style="text-align:center">Email: basavrajchoudapur@gmail.com</p>
      <p style="text-align:center">Phone: +91-7841861815</p>
      <script>console.log("Contact section loaded");</script>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 मेरी कंपनी। सभी अधिकार सुरक्षित।</p>
      <script>console.log("Footer rendered");</script>
    </div>
  </footer>
</body>
</html>

