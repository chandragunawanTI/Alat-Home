<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Home Kita</title>

    <!--Fonts-->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />

    <!--feather Icon-->
    <script src="https://unpkg.com/feather-icons"></script>

    <!--My Style-->
    <link rel="stylesheet" href="css/style.css" />
  </head>

  <body>
    <!--Navbar Start-->
    <nav class="navbar">
      <a href="#" class="navbar-logo">Home<span>Kita</span>.</a>

      <div class="navbar-nav">
        <a href="#home">Home</a>
        <a href="#about">Tentang kami</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Kontak</a>
      </div>

      <div class="navbar-extra">
        <a href="#" id="search"><i data-feather="search"></i></a>
        <a href="#" id="shopping-cart"><i data-feather="shopping-cart"></i></a>
        <a href="#" id="hamburger-menu"><i data-feather="menu"></i></a>
      </div>
    </nav>
    <!--Navbar end-->

    <!--Hero selection star-->
    <section class="hero" id="home">
      <main class="content">
        <h1>Selamat Datang di Website<span>Kami</span></h1>
        <p>Temukan furniture terbaik untuk rumah Anda.</p>
        <a href="#" class="cta">Belanja Sekarang</a>
      </main>
    </section>

    <!-- Hero selection end -->

    <!--About section star-->
    <section id="about" class="about">
      <h2><span>Tentang</span> Kami</h2>

      <div class="row">
        <div class="about-img">
          <img src="img/logo-removebg-preview.png" alt="Tentang Kami" />
        </div>
        <div class="content">
          <h3>Kenapa memilih toko kami</h3>
          <p>
            Selamat datang di Home Kita, platform e-commerce terpercaya yang
            menghadirkan berbagai kebutuhan rumah tangga dan furniture
            berkualitas tinggi untuk keluarga modern. Kami percaya bahwa rumah
            adalah tempat terbaik untuk menciptakan momen berharga, dan setiap
            detail di dalamnya mencerminkan kehangatan dan kenyamanan. Dengan
            berbagai pilihan produk yang dirancang untuk memenuhi kebutuhan
            estetika dan fungsional, kami hadir untuk membantu Anda menciptakan
            ruang yang sempurna, di mana kreativitas dan kenyamanan berjalan
            beriringan.
          </p>
          <p>
            Di Home Kita, kepuasan pelanggan adalah prioritas utama kami.
            Melalui komitmen pada kualitas, harga yang kompetitif, dan
            pengalaman belanja yang mudah, kami terus berinovasi untuk menjadi
            mitra terpercaya Anda. Didukung oleh layanan pelanggan yang ramah
            dan pengiriman yang cepat, kami siap membantu Anda menemukan produk
            terbaik sesuai dengan kebutuhan dan gaya hidup Anda. Jelajahi dunia
            belanja yang menyenangkan bersama kami, dan wujudkan rumah impian
            Anda dengan solusi terbaik dari kami.
          </p>
        </div>
      </div>
    </section>

    <!--About section end-->

    <!--Menu Setion star-->
    <section id="menu" class="menu">
      <h2><span>Menu</span> Kami</h2>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam voluptate
        sunt ut quia pariatur quas!
      </p>
      <div class="row">
        <div class="menu-card">
          <img
            src="menu/kipas angin.jpg"
            alt="kipas Angin"
            class="menu-card-img"
          />
          <h3 class="menu-card-title">- Kipas Angin -</h3>
          <p class="menu-card-price">Rp 120k</p>
        </div>
        <div class="menu-card">
          <img src="menu/kompor.jpeg" alt="kipas Angin" class="menu-card-img" />
          <h3 class="menu-card-title">- Kompor Gas -</h3>
          <p class="menu-card-price">Rp 250.000</p>
        </div>
        <div class="menu-card">
          <img src="menu/kulkas.jpg" alt="kulkas" class="menu-card-img" />
          <h3 class="menu-card-title">- Kulkas -</h3>
          <p class="menu-card-price">Rp 800.000</p>
        </div>
        <div class="menu-card">
          <img src="menu/meja.jpeg" alt="Meja" class="menu-card-img" />
          <h3 class="menu-card-title">- Meja -</h3>
          <p class="menu-card-price">Rp 60.000</p>
        </div>
        <div class="menu-card">
          <img src="menu/meja.jpeg" alt="Meja" class="menu-card-img" />
          <h3 class="menu-card-title">- Meja -</h3>
          <p class="menu-card-price">Rp 60.000</p>
        </div>
      </div>
    </section>

    <!--Menu Setion end-->

    <!--contact section start-->
    <section id="contact" class="contact">
      <h2><span>Kontak</span> Kami</h2>
      <p>
        Lorem, ipsum dolor sit amet consectetur adipisicing elit. Cum,
        repellendus.
      </p>

      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d63114.43848708848!2d116.07771388154259!3d-8.629328940547829!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2dcdbed93767f275%3A0xff85a2e125d182d0!2sKec.%20Labuapi%2C%20Kabupaten%20Lombok%20Barat%2C%20Nusa%20Tenggara%20Bar.!5e0!3m2!1sid!2sid!4v1736879458565!5m2!1sid!2sid"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          class="map"></iframe
        >
        <form action="">
          <div class="input-group">
            <i data-feather="user"></i>
            <input type="text" placeholder="Nama" />
          </div>
        <form action="">
          <div class="input-group">
            <i data-feather="mail"></i>
            <input type="text" placeholder="Email" />
          </div>
        <form action="">
          <div class="input-group"> 
            <i data-feather="phone"></i>
            <input type="text" placeholder="No hp" />
          </div>
          <button type="submit" class="btn">kirim pesan</button>
        </form>
      </div>
    </section>
    <!--contact section end-->

    <!---footer start-->
    <footer>
      <div class="sosial">
        <a href="#"><i data-feather="instagram"></i></a>
        <a href="#"><i data-feather="twitter"></i></a>
        <a href="#"><i data-feather="facebook"></i></a>
      </div>

      <div class="links">
        <a href="#home">Home</a>
        <a href="#about">Tentang kami</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Kontak</a>
      </div>

      <div class="credit">
        <p>Create by <a href="">Chandra gunawan</a>. | &copy; 2025.</p>
      </div>
    </footer>
    <!---foother and-->

    <!--Feather Icon-->
    <script>
      feather.replace();
    </script>

    <!--My Javascript-->
    <script src="js/script.js"></script>
  </body>
</html>

