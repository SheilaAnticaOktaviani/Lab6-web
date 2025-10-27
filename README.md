# Lab6-web
# PERTEMUAN 6
## Nama: SHEILA ANTICA OKTAVIANI
## Kelas: TI.24.AI
## NIM: 312410002
## Mata Kuliah: Pemrogaman Web
# INPUT Home HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Layout Sederhana</title>

  <!-- Bootstrap CSS (CDN) -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
    rel="stylesheet"
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH"
    crossorigin="anonymous"
  />

  <!-- Custom CSS -->
  <link rel="stylesheet" href="style.css" />
</head>
<body class="bg-page">

  <!-- Header -->
  <header class="brandbar py-3">
    <div class="container">
      <h1 class="brandtitle fw-bold text-secondary">Layout Sederhana</h1>
    </div>
  </header>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary shadow-sm">
    <div class="container">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#mainNav"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div id="mainNav" class="collapse navbar-collapse">
        <ul class="navbar-nav me-auto">
          <li class="nav-item">
            <a href="home.html" class="nav-link active">Home</a>
          </li>
          <li class="nav-item">
            <a href="artikel.html" class="nav-link">Artikel</a>
          </li>
          <li class="nav-item">
            <a href="about.html" class="nav-link">About</a>
          </li>
          <li class="nav-item">
            <a href="kontak.html" class="nav-link">Kontak</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="container mt-3">
    <div class="p-4 bg-light rounded shadow-sm">
      <h2 class="fw-bold mb-2">Hello World!</h2>
      <p class="lead text-secondary mb-3">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada
        tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec
        pretium nunc pretium ac.
      </p>
      <a class="btn btn-primary btn-lg" href="#">Learn more »</a>
    </div>
  </section>

  <!-- Main Content -->
  <main class="container my-4">
    <div class="row gx-4 gy-4">
      <!-- Main Column -->
      <div class="col-lg-8">

        <!-- 3 Circles -->
        <div class="row text-center g-4 mt-2">
          <div class="col-md-4">
            <div>
              <div class="circle bg-warning text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
          <div class="col-md-4">
            <div>
              <div class="circle bg-primary text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
          <div class="col-md-4">
            <div>
              <div class="circle bg-info text-white mx-auto d-flex align-items-center justify-content-center">120 × 120</div>
              <h5 class="mt-3 fw-semibold">Heading</h5>
              <p class="small text-secondary">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
              <a class="btn btn-light btn-sm" href="#">View detail</a>
            </div>
          </div>
        </div>

        <hr class="my-4" />

        <!-- Featurette 1 -->
        <article class="row align-items-start gy-3">
          <div class="col-4 col-sm-3">
            <div class="bg-secondary bg-opacity-50 text-center py-5 rounded">150 × 150</div>
          </div>
          <div class="col">
            <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
            <p class="mb-0 text-secondary">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
              malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
              est nunc, nec pretium nunc pretium ac.
            </p>
          </div>
        </article>

        <hr class="my-4" />

        <!-- Featurette 2 -->
        <article class="row align-items-start gy-3">
          <div class="col">
            <h3 class="h4 fw-bold text-dark mb-2">First featurette heading.</h3>
            <p class="mb-0 text-secondary">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat,
              malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra
              est nunc, nec pretium nunc pretium ac.
            </p>
          </div>
          <div class="col-4 col-sm-3">
            <div class="bg-secondary bg-opacity-50 text-center py-5 rounded">150 × 150</div>
          </div>
        </article>
      </div>

      <!-- Sidebar -->
      <aside class="col-lg-4">
        <div class="card mb-4">
          <div class="card-header bg-primary text-white fw-bold">Widget Header</div>
          <ul class="list-group list-group-flush">
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
            <li class="list-group-item"><a href="#">Widget Link</a></li>
          </ul>
        </div>

        <div class="card">
          <div class="card-header bg-primary text-white fw-bold">Widget Text</div>
          <div class="card-body text-secondary">
            Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla,
            vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.
          </div>
        </div>
      </aside>
    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-dark text-white py-3">
    <div class="container small">
      © 2025 - Universitas Pelita Bangsa
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
    crossorigin="anonymous"
  ></script>
</body>
</html>

# OUTPUT HOME HTML
![WhatsApp Image 2025-10-27 at 20 24 23_f98ea262](https://github.com/user-attachments/assets/d3bca2de-2a44-4df3-bbf5-97611e1ab896)
![WhatsApp Image 2025-10-27 at 20 24 39_4b695b4d](https://github.com/user-attachments/assets/5387a2b0-a176-49fb-98fe-ee7c5d7c091d)
# <img width="959" height="481" alt="image" src="https://github.com/user-attachments/assets/c05a3642-0e9d-43e9-8a57-c705be40e306" />


# INPUT ABOUT HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div id="container">

    <header>
        <h1>Layout Sederhana</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="artikel.html">Artikel</a>
        <a href="about.html" class="active">About</a>
        <a href="kontak.html">Kontak</a>
    </nav>

    <section id="hero">
        <h1>Tentang Kami</h1>
        <p>Website sederhana ini dibuat untuk latihan pembuatan layout menggunakan HTML dan CSS.</p>
    </section>

    <section id="wrapper">
        <section id="main">
            <article class="entry">
                <h2>Deskripsi Singkat</h2>
                <p>
                    Kami adalah tim pengembang web pemula yang fokus mempelajari dasar-dasar desain 
                    web modern menggunakan HTML5, CSS3, dan konsep layout responsif.
                </p>
                <p>
                    Tujuan kami adalah memahami struktur layout web yang baik agar bisa diterapkan
                    di proyek-proyek yang lebih kompleks.
                </p>
            </article>

            <hr class="divider">

            <article class="entry">
                <h2>Portfolio Kami</h2>
                <div class="row">
                    <div class="box">
                        <img src="https://dummyimage.com/150/1f5faa/fff.png" class="image-circle" alt="">
                        <h3>Project A</h3>
                        <p>Website Company Profile</p>
                    </div>
                    <div class="box">
                        <img src="https://dummyimage.com/150/db7d25/fff.png" class="image-circle" alt="">
                        <h3>Project B</h3>
                        <p>Aplikasi Web E-Commerce</p>
                    </div>
                    <div class="box">
                        <img src="https://dummyimage.com/150/3e73e6/fff.png" class="image-circle" alt="">
                        <h3>Project C</h3>
                        <p>Website Informasi Kampus</p>
                    </div>
                </div>
            </article>
        </section>

        <aside id="sidebar">
            <div class="widget-box">
                <h3 class="title">Tentang Penulis</h3>
                <p>
                    Mahasiswa Teknik Informatika yang sedang belajar pengembangan web dengan HTML, CSS, dan JavaScript.
                </p>
            </div>
        </aside>
    </section>

    <footer>
        <p>&copy; 2025 - Universitas Pelita Bangsa</p>
    </footer>

</div>
</body>
</html>

# OUTPUT ABOUT HTML
<img width="959" height="503" alt="image" src="https://github.com/user-attachments/assets/a309ff32-388c-49c8-8770-0e7a2b45d05e" />

# INPUT KONTAK HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kontak - Layout Sederhana</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div id="container">

    <header>
        <h1>Layout Sederhana</h1>
    </header>

    <nav>
        <a href="home.html">Home</a>
        <a href="artikel.html">Artikel</a>
        <a href="about.html">About</a>
        <a href="kontak.html" class="active">Kontak</a>
    </nav>

    <section id="hero">
        <h1>Hubungi Kami</h1>
        <p>Silakan isi form di bawah ini untuk mengirimkan pesan atau pertanyaan Anda.</p>
    </section>

    <section id="wrapper">
        <section id="main">
            <article class="entry">
                <h2>Formulir Kontak</h2>
                <form action="#" method="post" class="contact-form">
                    <label for="nama">Nama:</label><br>
                    <input type="text" id="nama" name="nama" placeholder="Masukkan nama Anda" required><br><br>

                    <label for="email">Email:</label><br>
                    <input type="email" id="email" name="email" placeholder="Masukkan email Anda" required><br><br>

                    <label for="pesan">Pesan:</label><br>
                    <textarea id="pesan" name="pesan" rows="6" placeholder="Tulis pesan Anda..." required></textarea><br><br>

                    <button type="submit" class="btn">Kirim Pesan</button>
                </form>
            </article>
        </section>

        <aside id="sidebar">
            <div class="widget-box">
                <h3 class="title">Informasi Kontak</h3>
                <p>
                    Email: info@universitaspb.ac.id<br>
                    Telepon: (021) 1234567<br>
                    Alamat: Jl. Pelita Bangsa No. 1, Bekasi
                </p>
            </div>
        </aside>
    </section>

    <footer>
        <p>&copy; 2025 - Universitas Pelita Bangsa</p>
    </footer>

</div>
</body>
</html>

# OUTPUT KONTAK HTML
<img width="959" height="502" alt="image" src="https://github.com/user-attachments/assets/1a20b77e-4890-4bdf-a2c8-d9bc61639534" />


