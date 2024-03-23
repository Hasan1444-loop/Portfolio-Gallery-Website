# Portfolio-Gallery-Website
Aygaz GENAI project
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yapay Zeka ve Finansal Analiz Galerisi</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <!-- Header -->
  <header
    style="background-color: #333; color: #fff; padding: 20px; display: flex; justify-content: space-between; align-items: center;">
    <div class="logo">
      <h1 style="margin: 0; color: #ffd700; font-style: italic;">Yapay Zeka ve Finansal Analiz Galerisi</h1>
    </div>
    <nav>
      <ul
        style="list-style-type: none; padding: 0; margin: 0; display: flex; align-items: center; justify-content: space-between;">
        <li><a href="index.html"
            style="text-decoration: none; color: #fff; font-weight: bold; transition: color 0.3s ease;">Ana
            Sayfa</a></li>
        <li><a href="portfolio.html"
            style="text-decoration: none; color: #fff; font-weight: bold; transition: color 0.3s ease;">Portföy</a>
        </li>
        <li><a href="financial-analysis.html"
            style="text-decoration: none; color: #fff; font-weight: bold; transition: color 0.3s ease;">Finansal
            Analiz</a></li>
        <li><a href="about.html"
            style="text-decoration: none; color: #fff; font-weight: bold; transition: color 0.3s ease;">Hakkımda</a>
        </li>
        <li><a href="contact.html"
            style="text-decoration: none; color: #fff; font-weight: bold; transition: color 0.3s ease;">İletişim</a>
        </li>
      </ul>
    </nav>
  </header>

  <!-- Main İçerik -->
  <main>
    <!-- Slider veya Hero Bölümü -->
    <section class="hero" style="background-color: #1e90ff; color: #fff; padding: 50px; text-align: center;">
      <h2 style="font-size: 24px;">Yapay Zeka ile Oluşturulan <span
          style="font-style: italic; color: black;">Sanat</span> ve <span
          style="font-style: italic; color: black;">Finansal Analiz</span> İçerikleri</h2>
      <!-- Slider veya Hero İçeriği -->
    </section>

    <!-- Finansal Analiz Bölümü -->
    <section class="financial-analysis" style="background-color: #fff; color: #333; padding: 50px; text-align: center;">
      <h2 style="color: #000000;">Finansal Analiz</h2>
      <p style="margin-bottom: 20px;">Yapay Zeka ile Oluşturulan Finansal Analiz İçerikleri: piyasa tahminleri
        gibi yapay zeka tarafından oluşturulan içeriklerin listelendiği bir bölüm.</p>
      <!-- Resim Ekle -->
      <img src="3NEpNVxG9bn1eMIzmI8v--1--3j8z5.jpg" alt="Resim Açıklaması"
        style="width: 15rem; vertical-align: middle;">
      <img src="Untitled design-images-1.jpg" alt="Resim Açıklaması" style="width: 15rem; vertical-align: middle;">
      <img src="Untitled design (1)-images-1.jpg" alt="Resim Açıklaması" style="width: 15rem; vertical-align: middle;">
      <img src="image10.jpg" alt="Resim Açıklaması" style="width: 15rem; vertical-align: middle;">

    </section>

    <!-- Komik Fıkralar ve Espiriler Bölümü -->
    <section class="funny-jokes" style="background-color: #ffe4b5; color: #000; padding: 50px; text-align: center;">
      <h2 style="font-style: italic; color: #8b4513; font-size: 20px;">Komik Fıkralar ve Espiriler Galerisi</h2>
      <article style="font-size: 16px;">
        <p>Yapay zeka tarafından üretilmiş en komik fıkralar ve esprilerin bulunduğu bir bölüm. Günün stresini
          atmak ve kahkahalarla dolu bir an geçirmek için mükemmel bir yer!</p>
      </article>
      <!-- Resimler -->
      <div class="image-gallery" style="display: flex; justify-content: center; margin-top: 20px;">
        <img src="2d134e7e0a734bce892ccade6f885dfatQpAEWe7H0D6wPOC-0.jpg" alt="Komik Resim 1"
          style="width: 200px; margin-right: 20px;">
        <img src="37dcc74973064301dc4d846dbaf4ac86G0USSpn2J1y8zanv-1.jpg" alt="Komik Resim 2"
          style="width: 200px; margin-right: 20px;">
        <img src="0928491e678841618cd7714a3ef5b65e6iStc7OYYT455Yv5-0.jpg" alt="Komik Resim 3" style="width: 200px;">
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer style="background-color: #333; color: #fff; padding: 20px; text-align: center;">
    <div class="social-media" style="margin-bottom: 20px;">
      <!-- Sosyal Medya Bağlantıları -->
    </div>
    <div class="copyright" style="font-size: 12px;">
      <!-- Telif Hakkı Bilgisi -->
    </div>
  </footer>
</body>

</html>

/* Genel Stil */
body {
 font-family: Arial, sans-serif;
 margin: 0;
 padding: 0;
 background-color: #f8f8f8;
}

/* Header Stili */
header {
 background-color: #333;
 color: #fff;
 padding: 20px;
 display: flex;
 /* Flexbox kullanarak içeriği yan yana hizala */
 justify-content: space-between;
 /* İçeriği sağa ve sola yasla */
 align-items: center;
}

.logo h1 {
 margin: 0;
 color: #ffd700;
 /* Başlık rengi: Sarı */
}

nav ul {
 list-style-type: none;
 padding: 0;
 margin: 0;
 display: flex;
 /* Flexbox kullanarak menü öğelerini yan yana hizala */
}

nav ul li {
 margin-right: 20px;
 /* Adjust the margin-right to increase or decrease space between items */
 width: 120px;
 /* Set the width of each navigation item */
 text-align: center;
 /* Center align the text within each navigation item */
}

nav ul li:last-child {
 margin-right: 0;
 /* Son öğenin sağ kenar boşluğunu kaldır */
}

nav ul li a {
 text-decoration: none;
 color: #fff;
 font-weight: bold;
 transition: color 0.3s ease;
}

nav ul li a:hover {
 color: #ffd700;
}

/* Main İçerik Stili */
main {
 margin: 50px;
}

.hero {
 background-color: #1e90ff;
 color: #fff;
 padding: 50px;
 text-align: center;
}

.financial-analysis {
 background-color: #fff;
 color: #333;
 padding: 50px;
 text-align: center;
}

.financial-analysis h2 {
 color: #0000FF;
 /* Alt başlık rengi: Mavi */
 margin-bottom: 20px;
}

.financial-analysis p {
 margin-bottom: 20px;
}

.financial-analysis img {
 width: 1.5rem;
 /* Resimlerin genişliği */
 height: auto;
 /* Orantılı bir şekilde boyutlandırma yapılır */
 display: inline-block;
 /* Resimlerin yatay olarak sıralanması sağlanır */
 margin-right: 10px;
 /* Resimler arasında boşluk bırakılır */
}

.portfolio {
 background-color: #f8f8f8;
 padding: 50px;
 text-align: center;
}

/* Footer Stili */
footer {
 background-color: #333;
 color: #fff;
 padding: 20px;
 text-align: center;
}

.social-media {
 margin-bottom: 20px;
}

.social-media a {
 color: #fff;
 text-decoration: none;
 margin-right: 10px;
}

.social-media a:hover {
 color: #ffd700;
}

/* Copyright Stili */
.copyright {
 font-size: 12px;
}
