# Mero-website
<!DOCTYPE html>
<html lang="ne">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>हाम्रो सेवा</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #333;
    }
    header {
      background: #006699;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background: #005580;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 1.5rem;
      max-width: 800px;
      margin: auto;
      background: white;
      margin-top: 1rem;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #003d5c;
      color: white;
      margin-top: 2rem;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>हाम्रो निर्माण तथा सजावट सेवा</h1>
  </header>

  <nav>
    <a href="#home">गृहपृष्ठ</a>
    <a href="#about">हाम्रो बारेमा</a>
    <a href="#services">सेवा</a>
    <a href="#contact">सम्पर्क</a>
  </nav>

  <section id="home">
    <h2>स्वागत छ!</h2>
    <p>हामी तपाईंको घर तथा अफिस निर्माण, फल सिलिङ, डेकोरेसन तथा रङ्ग सजावट सेवा प्रदान गर्छौं।</p>
  </section>

  <section id="about">
    <h2>हाम्रो बारेमा</h2>
    <p>हामी अनुभवी टोलीसहितको निर्माण कम्पनी हौं जसले गुणस्तरीय सेवा सुलभ मूल्यमा दिन्छ।</p>
  </section>

  <section id="services">
    <h2>हाम्रा सेवा</h2>
    <ul>
      <li>फल सिलिङ डिजाइन</li>
      <li>डेकोरेसन रङ्ग रंगाई</li>
      <li>निर्माण सम्बन्धी सम्पूर्ण सेवा</li>
      <li>भित्ताको डिजाइन र मरम्मत</li>
    </ul>
  </section>

  <section id="contact">
    <h2>सम्पर्क</h2>
    <p>फोन: ९८XXXXXXXX</p>
    <p>इमेल: example@yourservice.com</p>
    <p>स्थान: तपाईंको ठेगाना यहाँ</p>
  </section>

  <footer>
    © २०२५ हाम्रो सेवा | सबै अधिकार सुरक्षित
  </footer>
</body>
</html>
