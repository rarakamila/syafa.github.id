<!DOCTYPE html>
<html lang="id">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Website BPJS</title>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    />
    <style>
      body {
        font-family: Arial, sans-serif;
      }
      .header-text {
        font-size: 2rem;
        font-weight: bold;
        text-align: center;
        animation: lettering 2s steps(10) infinite;
      }
      @keyframes lettering {
        from {
          opacity: 0;
        }
        to {
          opacity: 1;
        }
      }
      .carousel img {
        height: 400px;
        object-fit: cover;
      }
      .info-box {
        transition: background 0.3s;
        cursor: pointer;
      }
      .info-box:hover {
        background: #f0f0f0;
      }
      .footer img {
        width: 50px;
        height: 50px;
      }
      .search-container {
        text-align: center;
        margin-bottom: 20px;
      }
      .search-input {
        width: 50%;
        padding: 10px;
      }
    </style>
  </head>
  <body>
    <div class="container mt-4">
      <h1 class="header-text">Website BPJS</h1>

      <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar BPJS</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        .navbar {
            background-color: #007bff;
        }
        .navbar-brand, .nav-link {
            color: white !important;
        }
        .nav-link:hover {
            color: #d1e7ff !important;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Tentang</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Layanan</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">FAQ</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Kontak</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Iuran BPJS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }
        .container {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
            text-align: center; /* Rata tengah semua teks */
        }
        label, select, input {
            display: block;
            width: 100%;
            margin-bottom: 10px;
            text-align: center; /* Rata tengah teks input & dropdown */
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator Iuran BPJS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 20px;
        }
        .container {
            max-width: 400px;
            margin: auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 2px 2px 12px rgba(0, 0, 0, 0.1);
        }
        label, select, input {
            display: block;
            width: 100%;
            margin-bottom: 10px;
        }
        button {
            background-color: #007bff;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
            margin-top: 10px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .rs-container {
            max-width: 600px;
            margin: auto;
            text-align: left;
            margin-top: 30px;
        }
        .rs-container h3 {
            text-align: center;
            margin-bottom: 15px;
        }
        .rs-container ul {
            padding: 0;
            list-style-type: none;
        }
        .rs-container li {
            background: #f9f9f9;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 5px;
            box-shadow: 1px 1px 5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <h2>Kalkulator Iuran BPJS</h2>
    <div class="container">
        <label for="kelas">Pilih Kelas BPJS:</label>
        <select id="kelas">
            <option value="150000">Kelas 1 - Rp150.000</option>
            <option value="100000">Kelas 2 - Rp100.000</option>
            <option value="42000">Kelas 3 - Rp42.000</option>
        </select>
        
        <label for="jumlah">Jumlah Anggota Keluarga:</label>
        <input type="number" id="jumlah" min="1" value="1">
        
        <button onclick="hitungIuran()">Hitung Iuran</button>
        
        <h3>Total Iuran: Rp <span id="total">0</span></h3>
    </div>
<ul>

</ul>
    
    <script>
        function hitungIuran() {
            let kelas = document.getElementById("kelas").value;
            let jumlah = document.getElementById("jumlah").value;
            let total = kelas * jumlah;
            document.getElementById("total").innerText = total.toLocaleString("id-ID");
        }
    </script>
</body>
</html>


      <!DOCTYPE html>
      <html lang="id">
        <head>
          <meta charset="UTF-8" />
          <meta
            name="viewport"
            content="width=device-width, initial-scale=1.0"
          />
          <title>Slideshow Gambar</title>
          <style>
            /* Desain gambar dalam slider */
            .slider {
              display: flex;
              overflow: hidden;
              width: 100%;
              border-radius: 15px; /* Sudut tumpul pada kontainer */
            }

            .slider img {
              width: 100%;
              height: auto;
              border-radius: 15px; /* Sudut tumpul pada gambar */
            }

            /* Animasi geser gambar secara otomatis */
            @keyframes slide {
              0% {
                transform: translateX(0);
              }
              100% {
                transform: translateX(-100%);
              }
            }

            .slider {
              animation: slide 15s infinite; /* 15 detik untuk satu putaran */
            }
          </style>
        </head>
        <body>
          <script>
            // JavaScript tambahan (opsional) untuk pengaturan lebih lanjut jika diperlukan
          </script>
        </body>
      </html>

      <!-- Carousel Controls (Optional) -->
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExample"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExample"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
      </button>
    </div>

    <!-- CSS untuk tumpul lebih besar -->
    <style>
      .carousel-item img {
        border-radius: 20px; /* Mengatur sudut tumpul */
      }
    </style>

    <!-- CSS untuk tumpul lebih besar -->
    <style>
      .carousel-item img {
        border-radius: 20px; /* Mengatur sudut tumpul */
      }
    </style>

    <!DOCTYPE html>
    <html lang="id">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Daftar Rumah Sakit & Kantor BPJS Kesehatan</title>
        <style>
          body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f9;
          }
          h1 {
            text-align: center;
            color: #333;
          }
          .container {
            display: flex;
            flex-direction: column;
            gap: 20px;
            max-width: 800px;
            margin: auto;
          }
          .card {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
          }
          .card h2 {
            margin: 0;
            font-size: 1.5em;
            color: #2c3e50;
          }
          .card p {
            font-size: 1em;
            color: #7f8c8d;
          }
          .card a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px;
            background-color: #2980b9;
            color: white;
            text-decoration: none;
            border-radius: 5px;
          }
          .card a:hover {
            background-color: #3498db;
          }
        </style>
      </head>
      <body>
        <h1>Daftar Rumah Sakit dan Kantor BPJS Kesehatan</h1>

        <div class="container">
          <!-- Rumah Sakit Section -->
          <div class="card">
            <h2>Rumah Sakit Umum Pusat (RSUP) Dr. Mohammad Hoesin Palembang</h2>
            <p>Alamat: Jalan Jenderal Sudirman No. 589, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Rumah+Sakit+Umum+Pusat+Dr.+Mohammad+Hoesin+Palembang/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Rumah Sakit Siloam Sriwijaya</h2>
            <p>Alamat: Jalan Demang Lebar Daun No. 101, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Rumah+Sakit+Siloam+Sriwijaya/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Rumah Sakit Muhammadiyah Palembang</h2>
            <p>Alamat: Jalan Jenderal Sudirman No. 527, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Rumah+Sakit+Muhammadiyah+Palembang/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Rumah Sakit Bhayangkara Palembang</h2>
            <p>Alamat: Jalan Jenderal Sudirman No. 355, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Rumah+Sakit+Bhayangkara+Palembang/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Rumah Sakit Pusri Palembang</h2>
            <p>Alamat: Jalan Raya Palembang-Prabumulih No. 1, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Rumah+Sakit+Pusri+Palembang/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <!-- Kantor BPJS Kesehatan Section -->
          <div class="card">
            <h2>Kantor BPJS Kesehatan Cabang Palembang</h2>
            <p>Alamat: Jalan Pahlawan No. 10, Palembang</p>
            <a
              href="https://www.google.com/maps/place/Kantor+BPJS+Kesehatan+Cabang+Palembang/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Kantor BPJS Kesehatan Kabupaten Ogan Ilir</h2>
            <p>Alamat: Jalan Lintas Sumatera No. 123, Indralaya</p>
            <a
              href="https://www.google.com/maps/place/Kantor+BPJS+Kesehatan+Kabupaten+Ogan+Ilir/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>

          <div class="card">
            <h2>Kantor BPJS Kesehatan Kabupaten Musi Banyuasin</h2>
            <p>Alamat: Jalan Lintas Timur No. 456, Sekayu</p>
            <a
              href="https://www.google.com/maps/place/Kantor+BPJS+Kesehatan+Kabupaten+Musi+Banyuasin/"
              target="_blank"
              >Lihat di Google Maps</a
            >
          </div>
        </div>
      </body>
    </html>

    <!-- Informasi BPJS -->
    <div class="row mt-4 g-3">
      <div
        class="col-md-4 col-sm-12 info-box p-3 border text-center"
        onclick="changeColor(this)"
      >
        <h5>🔹 Apa Itu BPJS?</h5>
        <p>BPJS (Badan Penyelenggara Jaminan Sosial) adalah program</p>
        <p>jaminan kesehatan dari pemerintah untuk seluruh rakyat Indonesia</p>
      </div>

      <div
        class="col-md-4 col-sm-12 info-box p-3 border text-center"
        onclick="changeColor(this)"
      >
        <h5>🔹 Manfaat BPJS</h5>
        <p>BPJS Kesehatan menjamin akses layanan medis, mulai dari klinik</p>
        <p>hingga rumah sakit, dengan biaya yang lebih ringan atau bahkan gratis.</p>
      </div>

      <div
        class="col-md-4 col-sm-12 info-box p-3 border text-center"
        onclick="changeColor(this)"
      >
        <h5>🔹 Cara Mendaftar</h5>
        <p>Pendaftaran bisa dilakukan secara online melalui aplikasi<p>
        <p>Mobile JKN atau datang langsung ke kantor BPJS terdekat.</p>
      </div>
    </div>

    <!-- CSS -->
    <style>
      .info-box {
        background-color: #f8f9fa; /* Warna default */
        text-align: center;
        cursor: pointer;
        transition: background-color 0.3s ease;
        border-radius: 10px;
        box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
      }

      .info-box.clicked {
        background-color: #007bff; /* Warna saat diklik */
        color: white;
      }
    </style>

    <!-- JavaScript -->
    <script>
      function changeColor(element) {
        element.classList.toggle("clicked");
      }
    </script>
    

    <!-- Tentang Kami -->
    <section class="container text-center my-5">
      <h2 class="mb-4">Tentang Kami</h2>

      <div class="row justify-content-center">
        <!-- Sarah -->
        <div
          class="col-md-4 text-center profile-card"
          onclick="changeColor(this)"
        >
          <div class="profile-container">
            <img
              src="sarah.jpeg"
              alt="Sarah Nur Arna Cholifah"
              class="profile-img mb-3"
            />
          </div>
          <div class="text-box">
            <h4>Sarah Nur Arna Cholifah</h4>
            <p>
              Teknologi, Pemrograman, & Pengembangan Game, Coding, Greenfoot,
              Editing Canva, Desain & Kreativitas
            </p>
            <div class="d-grid gap-2">
              <a
                href="mailto:sarahnac19@gmail.com"
                class="btn btn-primary rounded-pill"
                >📧 Email</a
              >
              <a
                href="https://instagram.com/sarahchlfah"
                target="_blank"
                class="btn btn-danger rounded-pill"
                >📸 Instagram</a
              >
              <a
                href="https://wa.me/62895604966609"
                target="_blank"
                class="btn btn-success rounded-pill"
                >💬 WhatsApp</a
              >
            </div>
          </div>
        </div>

        <!-- Syafa -->
        <div
          class="col-md-4 text-center profile-card"
          onclick="changeColor(this)"
        >
          <div class="profile-container">
            <img
              src="syafa.jpeg"
              alt="Syafa Kamila Azzahra"
              class="profile-img mb-3"
            />
          </div>
          <div class="text-box">
            <h4>Syafa Kamila Azzahra</h4>
            <p>
              I'm Syafa, but you can call me Ara, Zahra, or even "Babe" if u
              dare
            </p>
            <p>
              Jack of all trades, master of makin’ things work Multitasking?
              That’s my middle name
            </p>
            <div class="d-grid gap-2">
              <a
                href="mailto:rarak1562@gmail.com"
                class="btn btn-primary rounded-pill"
                >📧 Hit me up</a
              >
              <a
                href="https://wa.me/6285789970710"
                target="_blank"
                class="btn btn-success rounded-pill"
                >💬 Slide in my DM</a
              >
            </div>
          </div>
        </div>

        <!-- Eka -->
        <div
          class="col-md-4 text-center profile-card"
          onclick="changeColor(this)"
        >
          <div class="profile-container">
            <img
              src="eka.jpg"
              alt="Eka Putri Apriliani"
              class="profile-img mb-3"
            />
          </div>
          <div class="text-box">
            <h4>Eka Putri Apriliani</h4>
            <p>
              🛠 Keterampilan saya meliputi teknologi, desain, kreativitas, serta
              kerja sama tim dan kepemimpinan yang bermanfaat bagi saya dan
              orang lain.
            </p>
            <div class="d-grid gap-2">
              <a
                href="mailto:ekaputriapriliani17@gmail.com"
                class="btn btn-primary rounded-pill"
                >📧 Email</a
              >
              <a
                href="https://instagram.com/kaaptrii_"
                target="_blank"
                class="btn btn-danger rounded-pill"
                >📸 Instagram</a
              >
              <a
                href="https://wa.me/62895373144433"
                target="_blank"
                class="btn btn-success rounded-pill"
                >💬 WhatsApp</a
              >
            </div>
          </div>
        </div>
      </div>
    </section>

    <style>
      /* Animasi Goyang Terus */
      @keyframes shake {
        0% {
          transform: rotate(2deg);
        }
        50% {
          transform: rotate(-2deg);
        }
        100% {
          transform: rotate(2deg);
        }
      }

      /* Efek animasi pada gambar */
      .profile-img {
        border-radius: 50%;
        width: 150px; /* Ukuran foto */
        height: 150px;
        object-fit: cover;
        animation: shake 0.3s infinite alternate; /* Animasi goyang terus */
      }

      /* Kartu hover + klik */
      .profile-card {
        transition: background-color 0.3s, transform 0.2s;
        padding: 15px;
        border-radius: 15px;
        box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        cursor: pointer;
      }

      /* Bingkai bulat untuk teks */
      .text-box {
        background-color: rgba(255, 255, 255, 0.8);
        border-radius: 50%;
        padding: 20px;
        display: inline-block;
        text-align: center;
        width: 90%;
        max-width: 250px;
        margin-top: 10px;
      }

      /* Efek klik ubah warna */
      .clicked {
        background-color: #ffcccb !important; /* Warna berubah saat diklik */
      }
    </style>

    <script>
      function changeColor(element) {
        element.classList.toggle("clicked");
      }
    </script>

    <style>
      /* Efek hover untuk foto */
      .profile-img {
        transition: transform 0.3s ease-in-out;
      }
      .profile-img:hover {
        transform: rotate(5deg) scale(1.1);
      }

      /* Efek hover & klik untuk kartu */
      .profile-card {
        transition: background-color 0.3s, transform 0.2s;
        padding: 15px;
        border-radius: 15px;
        box-shadow: 0px 4px 6px rgba(0, 0, 0,


      <!-- CSS -->
      <style>
        /* Container untuk efek bingkai */
        .profile-container {
          display: inline-block;
          padding: 5px;
          border-radius: 50%;
          background: white;
          box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }

        /* Foto profil dengan bingkai bulat */
        .profile-img {
          width: 150px;
          height: 150px;
          border-radius: 50%;
          transition: transform 0.3s ease-in-out;
        }

        /* Efek goyang saat hover */
        .profile-container:hover {
          transform: rotate(5deg) scale(1.1);
        }

        /* Bingkai untuk teks */
        .text-box {
          background: white;
          padding: 15px;
          border-radius: 20px;
          box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
          margin-top: 10px;
        }
    </style>

    <!-- CSS -->
    <style>
      /* Container untuk efek bingkai */
      .profile-container {
        display: inline-block;
        padding: 5px;
        border-radius: 50%;
        background: white;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
      }

      /* Foto profil dengan bingkai bulat */
      .profile-img {
        width: 150px;
        height: 150px;
        border-radius: 50%;
        transition: transform 0.3s ease-in-out;
      }

      /* Efek goyang saat hover */
      .profile-container:hover {
        transform: rotate(5deg) scale(1.1);
      }
    </style>

    <!-- Footer -->
    <footer
      class="mt-4 text-center py-4"
      style="background-color: #f0f8ff; color: #000"
    >
      <div class="container">
        <!-- Logo -->
        <div class="mb-3">
          <img
            src="logo_bpjs_transparent.png"
            alt="Logo BPJS"
            style="height: 100px; margin-right: 10px"
          />
          <img
            src="logo_uigm_transparent.png"
            alt="Logo UIGM"
            style="height: 95px"
          />
        </div>

        <!-- Kontak UIGM -->
        <div class="d-flex flex-column align-items-center gap-2 mt-3">
          <a
            href="https://maps.app.goo.gl/kCPfXviH1eE7dGyo9"
            target="_blank"
            class="btn btn-danger w-100"
          >
            📍 Alamat: Jl. Jend. Sudirman No.629, Palembang
          </a>
          <a href="mailto:info@uigm.ac.id" class="btn btn-primary w-100">
            📧 Email: info@uigm.ac.id
          </a>
          <a href="tel:+627113511755" class="btn btn-success w-100">
            📞 Telepon: 0711-3511755
          </a>
          <a
            href="https://wa.me/6281271278811"
            target="_blank"
            class="btn btn-success w-100"
          >
            💬 WhatsApp: 0812-7127-8811
          </a>
        </div>

        <!-- Tombol Lokasi & WhatsApp -->
        <div class="mt-3">
          <a
            href="https://maps.app.goo.gl/kCPfXviH1eE7dGyo9"
            target="_blank"
            class="btn btn-primary mx-2"
            >📍 Lokasi UIGM</a
          >
          <a
            href="https://wa.me/6281271278811"
            target="_blank"
            class="btn btn-success mx-2"
            >💬 Chat WhatsApp</a
          >
        </div>

        <!-- Hak Cipta -->
        <div class="mt-3">
          <p class="mb-0">
            © 2025 Universitas Indo Global Mandiri | Semua Hak Dilindungi
          </p>
        </div>
        <!-- Disclaimer Berjalan -->
        <marquee
          behavior="scroll"
          direction="left"
          style="
            background-color: #f42c2c;
            color: #ffffff;
            padding: 10px;
            font-weight: bold;
          "
        >
          ⚠️ Disclaimer: Website ini dibuat oleh mahasiswa UIGM dan bukan situs
          resmi BPJS. Kami mohon maaf jika terdapat kesalahan informasi.
        </marquee>
      </div>
    </footer>
  </body>
</html>

