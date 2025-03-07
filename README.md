<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />

    <!--my css-->
    <link rel="stylesheet" href="style.css" />

    <title>My Portofolio | M.Syahid Islamy</title>
  </head>
  <body style="background-color: blanchedalmond">
    <!--navbar-->
    <nav class="navbar navbar-expand-lg navbar-dark navbar fixed-top" style="background-color: #571b04">
      <div class="container">
        <a class="navbar-brand" href="#">M.Syahid I</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">About</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#projects"> Projects </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contacts">Contacts</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!--akhir  navbar-->

    <!--awal jumbotron-->
    <section id="home" class="jumbotron text-center">
      <img src="img/comics.jpg" alt="M.Syahid" width="200" height="210" class="rounded-circle" /><!--gunakan class="rounded-circle",untuk mengatur bingkai-->
      <h1 class="display-4">M.Syahid</h1>
      <p class="lead">Software Engginer | Developer</p>
    </section>
    <br /><br /><br /><br />
    <!--akhir jumbotron-->

    <!--about-->
    <section id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>About Me</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>
              Halo! Nama saya Muhammad Syahid Islamy, seorang Data Analyst atau Junior Programmer. Saat ini, saya mendalami bidang analisis data, pemrograman Java, dan teknologi blockchain. Saya memiliki antusiasme besar untuk memecahkan
              masalah menggunakan data dan teknologi. Dalam beberapa tahun terakhir, saya telah mengembangkan keterampilan di berbagai bidang, termasuk pemrograman, manajemen basis data, dan pengembangan blockchain.
            </p>
          </div>
          <div class="col-md-4">
            <p>
              Saya memulai perjalanan saya di dunia teknologi dengan dasar yang kuat dari SMK Telkom Jakarta, di mana saya mendapatkan pelatihan praktis dan teoretis dalam teknologi informasi. Kini, saya terus memperdalam pemahaman saya di
              bidang-bidang yang saya minati, termasuk eksplorasi dan analisis data yang bertujuan untuk memberikan solusi nyata bagi berbagai tantangan bisnis.
            </p>
          </div>
        </div>
      </div>
    </section>
    <br /><br />
    <br /><br />
    <!--akhir about-->

    <!--projects-->
    <section id="projects">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>My Project</h2>
          </div>
        </div>
        <div class="row justify-content-evenly">
          <!--justify evenly,untuk mengatur tampilan gambar spasi kiri kanan-->
          <div class="col-md-4 mb-3">
            <!--md untuk mengatur tampilan di hp-->
            <div class="card">
              <img src="img/shubham-dhage-HyxJ0yqa_8Q-unsplash.jpg" class="card-img-top" alt="projects1" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <!--mb atau margin button untuk mengatur jarak di tampilan hp antar gambar-->
            <div class="card">
              <img src="img/markus-spiske-70Rir5vB96U-unsplash.jpg" class="card-img-top" alt="projects2" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/biner.jpg" class="card-img-top" alt="projects3" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/markus-spiske-70Rir5vB96U-unsplash.jpg" class="card-img-top" alt="projects4" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card">
              <img src="img/markus-spiske-70Rir5vB96U-unsplash.jpg" class="card-img-top" alt="projects5" />
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <br /><br /><br /><br />
    <!--akhir projects-->

    <!--Contacts-->
    <section id="contacts">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Contact Me</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6"></div>
          <!--col md8,untuk mengatur textfield agar tidak terlalu panjang-->
          <form>
            <!--textfield Email-->
            <div class="mb-3">
              <label for="email" class="form-label">Email</label>
              <input type="email" class="form-control" id="Email" aria-describedby="emai" />
            </div>
            <!--textfield Nama-->
            <div class="mb-3">
              <label for="name" class="form-label">Masukkan Nama Lengkap Anda</label>
              <input type="text" class="form-control" id="name" aria-describedby="name" />
            </div>

            <!--Text Area-->
            <div class="mb-3">
              <label for="Textarea" class="form-label">Catatan</label>
              <textarea class="form-control" id="Textarea" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Kirim</button>
          </form>
          <br />
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#571b04"
          fill-opacity="1"
          d="M0,256L48,261.3C96,267,192,277,288,256C384,235,480,181,576,165.3C672,149,768,171,864,197.3C960,224,1056,256,1152,250.7C1248,245,1344,203,1392,181.3L1440,160L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!--Akhir Contacts-->

    <!--Footer-->
    <!--pb atau padding break berguna untuk mengatur jarak-->
    <footer class="text-center pb-5" style="background-color: #571b04; text-white">
      <!--class="text-white" digunakan untuk memutihkan link-->
      <!--fw atau font-white-wight-bold digunakan untuk menebalkan-->
      <a href="https://wa.me/+62889224097">WHATSAPP</a
      ><!--arahkan ke chat wa kita-->
      <p class="text-white">Created By <a href="https://www.instagram.com/katasandi9653/" class="text-white">Syahid</a></p>
    </footer>
    <!--Akhir Footer-->

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
  </body>
</html>
