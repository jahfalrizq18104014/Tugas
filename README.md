<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css"
    integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css"
    integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
  <style>
    article,
    aside,
    figcaption,
    figure,
    footer,
    header,
    hgroup,
    main,
    nav,
    section {
      display: block;
    }

    body {
      font-family: Quicksand;
    }

    .btn-secondary:hover {
      background-color: #e6e6e6 !important;
    }

    .btn-secondary {
      background-color: #fff !important;
      color: #757575 !important;
      border-color: #e3e3e3 !important;
    }

    .btn-primary {
      color: #fff !important;
      font-family: Quicksand, sans-serif;
      font-weight: 500;
      background-color: #ff5483 !important;
      border-color: #ff5483 !important;
    }

    .btn-primary:hover {
      background-color: #fa4172 !important;
    }

    .btn {
      display: inline-block;
      font-weight: 400;
      color: #212529;
      text-align: center;
      vertical-align: middle;
      -webkit-user-select: none;
      -moz-user-select: none;
      -ms-user-select: none;
      user-select: none;
      background-color: transparent;
      border: 1px solid transparent;
      padding: .375rem .75rem;
      font-size: 1rem;
      line-height: 1.5;
      border-radius: .25rem;
      transition: color .15s ease-in-out, background-color .15s ease-in-out, border-color .15s ease-in-out, box-shadow .15s ease-in-out;
    }

    a.btn {
      letter-spacing: 2px;
      text-transform: uppercase !important;
      font-size: 12px !important;
    }

    .home-bg {
      min-height: 728px !important;
      color: #fff;
      margin-top: -5em;
      z-index: -1;
      padding-top: 11em;
      background-repeat: no-repeat;
      background-color: #2d3e50;
      background: linear-gradient(rgba(45, 62, 80, .25), rgba(45, 62, 80, .25)), url(https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-hero-new.jpg);
      background-position: top;
    }

    .partner-home {
      background: #2d3e50;
      color: #fff;
    }

    .cta-box {
      background-image: url(https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-cta-bg.jpg), url(https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-cta-network.png);
      background-position: right top, -200px center;
      background-repeat: no-repeat, no-repeat;
      background-color: #f2f2f2;
    }

    .success-story {
      background: #181820;
      background: -moz-linear-gradient(-45deg, #181820 0, #2d3e50 100%);
      background: -webkit-gradient(left top, right bottom, color-stop(0, #181820), color-stop(100%, #2d3e50));
      background: -webkit-linear-gradient(-45deg, #181820 0, #2d3e50 100%);
      background: -o-linear-gradient(-45deg, #181820 0, #2d3e50 100%);
      background: -ms-linear-gradient(-45deg, #181820 0, #2d3e50 100%);
      background: linear-gradient(135deg, #181820 0, #2d3e50 100%);
    }

    .container-fluid {
      width: 100%;
      padding-right: 15px;
      padding-left: 15px;
      margin-right: auto;
      margin-left: auto;
    }

    .white-bg {
      background-color: #fff;
    }



    .img-graduate-profile {
      object-fit: cover;
      width: 100px;
      height: 100px;
      border-radius: 50%;
    }

    @media (min-width: 768px) {
      .img-graduate-profile {
        object-fit: cover;
        width: 55px;
        height: 55px;
        border-radius: 50%;
      }
    }

    @media (min-width: 1200px) {
      .col-xl-8 {
        -ms-flex: 0 0 66.666667%;
        flex: 0 0 66.666667%;
        max-width: 66.666667%;
      }
    }

    .ellipsis {
      text-overflow: ellipsis;
      white-space: nowrap;
      overflow: hidden;
    }

    .tipe {
      font-size: .7em;
      color: #a2a2a2;
    }

    .footer-commons img.aba {
      height: 70px;
      width: auto;
    }

    .footer-commons img.afwc {
      height: 30px;
      width: auto;
    }

    .nav-link {
      font-size: 14px;
      color: white !important;
      margin: 0 12px;
    }

    .nav-link.dark {
      font-size: 14px;
      color: black !important;
      margin: 0 12px;
    }

    .award-section {
      background-color: #dee2e6;
      padding: 30px 15px;
      text-align: center;
    }

    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      font-family: Quicksand, sans-serif !important;
      font-weight: 300 !important;
    }
  </style>

</head>

<body class="spy" data-spy="scroll" data-target="#spied">
  <nav class="navbar navbar-expand-lg navbar-light sticky-top" style="background:transparent;z-index:1000;">
    <div class="container">


      <a class="navbar-brand" href="#"><img src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/new-ui-logo.png"
          alt="Dicoding Indonesia"></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Academy <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Challenge</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Event</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Job</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Developer</a>
          </li>
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <a href="https://www.dicoding.com/login" id="login"
            class="btn btn-secondary mr-2 my-2 my-sm-0 d-none d-lg-block">Masuk</a>
          <a href="https://www.dicoding.com/registration"
            class="btn btn-primary my-2 my-sm-0 d-none d-lg-block">Daftar</a>
        </form>
      </div>
    </div>
  </nav>
  <div class="container-fluid home-bg text-center">
    <div class="container">
      <h1>Bangun Karirmu Sebagai Developer Profesional</h1>
      <div>Jadilah tuan rumah di negeri sendiri dengan belajar langsung dari para inovator dan developer expert</div>
    </div>
  </div>
  <div class="container-fluid award-section py-5">
    <div class="row">
      <div class="col-lg-4 col-md-8 col-sm-12 mx-auto">
        <h2 class="mb-4">Program Kami</h2>
        <div class="row">
          <div class="col-6"> <a href="https://www.dicoding.com/kartuprakerja">
              <div class="white-bg rounded shadow p-4"> <img
                  src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/prakerja-logo.png"
                  style="object-fit: contain;height: 70px;max-width: 100%;" alt="Logo Prakerja"> </div>
            </a> </div>
          <div class="col-6"> <a href="https://www.dicoding.com/kampusmerdeka" class="remove-style-link">
              <div class="white-bg rounded shadow p-4"> <img
                  src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/kampus-merdeka-logo.png"
                  style="object-fit: contain;height: 70px;max-width: 100%;" alt="Logo Kampus Merdeka"> </div>
            </a> </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container my-5 empat-pilar">
    <div class="row mb-4">
      <div class="col-sm-8 mx-auto text-center">
        <h2 class="my-4">4 Pilar yang Dapat Kamu Manfaatkan</h2>
        <p>Berikut ini adalah 4 pilar yang kami siapkan untuk membantumu membangun karir sebagai developer profesional.
        </p>
      </div>
    </div>
    <div class="row pb-5">
      <div class="col-lg-3 col-md-6 text-center mt-4"> <a href="https://www.dicoding.com/academies"
          class="remove-style-link"> </a>
        <div class="white-bg shadow rounded"><a href="https://www.dicoding.com/academies" class="remove-style-link">
            <div class="rounded-top bg-academy pt-2"></div>
          </a>
          <div class="card-body"><a href="https://www.dicoding.com/academies" class="remove-style-link"> <img
                src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-academy.png"
                data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-academy.png"
                class="lazy img-fluid d-block mx-auto mb-2 img-pilar" alt="Dicoding Academy" style="display: block;">
              <noscript>
                <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-academy.png'
                  class='noscript noscript-img img-fluid d-block mx-auto mb-2 img-pilar' alt='Dicoding Academy' />
              </noscript>
              <h4><b>Academy</b></h4>
              <p class="mb-4" data-equal-height="pilar-content" style="height: 168px;">Belajar menggunakan kurikulum
                yang telah divalidasi industri IT internasional seperti Google, Microsoft, dan LINE. Diskusikan Code
                yang kamu tulis dengan para Expert.</p>
            </a><a href="https://www.dicoding.com/academies" class="d-block mt-3 link-detail">Lihat Academy <i
                class="fas fa-arrow-circle-right"></i> </a> </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 text-center mt-4"> <a href="https://www.dicoding.com/challenges"
          class="remove-style-link"> </a>
        <div class="white-bg shadow rounded"><a href="https://www.dicoding.com/challenges" class="remove-style-link">
            <div class="rounded-top bg-challenge pt-2"></div>
          </a>
          <div class="card-body"><a href="https://www.dicoding.com/challenges" class="remove-style-link"> <img
                src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-challenge.png"
                data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-challenge.png"
                class="lazy img-fluid d-block mx-auto mb-2 img-pilar" alt="Dicoding Challenge" style="display: block;">
              <noscript>
                <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-challenge.png'
                  class='noscript noscript-img img-fluid d-block mx-auto mb-2 img-pilar' alt='Dicoding Challenge' />
              </noscript>
              <h4><b>Challenge</b></h4>
              <p class="mb-4" data-equal-height="pilar-content" style="height: 168px;">Uji kemampuanmu dengan mengikuti
                Challenge yang diselenggarakan oleh perusahaan IT nasional dan multi-nasional.</p>
            </a><a href="https://www.dicoding.com/challenges" class="d-block mt-3 link-detail">Lihat Challenge <i
                class="fas fa-arrow-circle-right"></i> </a> </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 text-center mt-4"> <a href="https://www.dicoding.com/events"
          class="remove-style-link"> </a>
        <div class="white-bg shadow rounded"><a href="https://www.dicoding.com/events" class="remove-style-link">
            <div class="rounded-top bg-event pt-2"></div>
          </a>
          <div class="card-body"><a href="https://www.dicoding.com/events" class="remove-style-link"> <img
                src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-event.png"
                data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-event.png"
                class="lazy img-fluid d-block mx-auto mb-2 img-pilar" alt="Dicoding Event" style="display: block;">
              <noscript>
                <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-event.png'
                  class='noscript noscript-img img-fluid d-block mx-auto mb-2 img-pilar' alt='Dicoding Event' />
              </noscript>
              <h4><b>Event</b></h4>
              <p class="mb-4" data-equal-height="pilar-content" style="height: 168px;">Bangun jejaring luas. Temui
                langsung para pelaku IT untuk saling berbagi dan belajar. Cari Event terdekat dari kotamu.</p>
            </a><a href="https://www.dicoding.com/events" class="d-block mt-3 link-detail">Lihat Event <i
                class="fas fa-arrow-circle-right"></i> </a> </div>
        </div>
      </div>
      <div class="col-lg-3 col-md-6 text-center mt-4"> <a href="https://www.dicoding.com/jobs"
          class="remove-style-link"> </a>
        <div class="white-bg shadow rounded"><a href="https://www.dicoding.com/jobs" class="remove-style-link">
            <div class="rounded-top bg-job pt-2"></div>
          </a>
          <div class="card-body"><a href="https://www.dicoding.com/jobs" class="remove-style-link"> <img
                src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-job.png"
                data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-job.png"
                class="lazy img-fluid d-block mx-auto mb-2 img-pilar" alt="Dicoding Job" style="display: block;">
              <noscript>
                <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-thumb-job.png'
                  class='noscript noscript-img img-fluid d-block mx-auto mb-2 img-pilar' alt='Dicoding Job' />
              </noscript>
              <h4><b>Job Platform</b></h4>
              <p class="mb-4" data-equal-height="pilar-content" style="height: 168px;">Cari lowongan pekerjaan khusus
                developer. Untuk perusahaan, temukan talenta digital yang Anda butuhkan. Bersama membangun ekosistem IT
                Indonesia.</p>
            </a><a href="https://www.dicoding.com/jobs" class="d-block mt-3 link-detail">Lihat Job Platform <i
                class="fas fa-arrow-circle-right"></i> </a> </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid partner-home p-5">
    <div class="container">
      <div class="row mb-4">
        <div class="col-sm-8 mx-auto text-center">
          <h2 class="my-4">Partner Kami</h2>
          <p>Dicoding bekerjasama dengan perusahaan teknologi dunia untuk membangun ekosistem IT Indonesia.</p>
        </div>
      </div>
      <div class="row mt-5 mb-3">
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-alcatel.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-alcatel.png"
            class="lazy img-fluid d-block mx-auto" alt="Alcatel Lucent" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-alcatel.png'
              class='noscript noscript-img img-fluid d-block mx-auto' alt='Alcatel Lucent' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-aws-educate.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-aws-educate.png"
            class="lazy img-fluid d-block mx-auto" alt="AWS Educate" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-aws-educate.png'
              class='noscript noscript-img img-fluid d-block mx-auto' alt='AWS Educate' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-google.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-google.png"
            class="lazy img-fluid d-block mx-auto" alt="Google" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-google.png'
              class='noscript noscript-img img-fluid d-block mx-auto' alt='Google' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-ibm.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-ibm.png"
            class="lazy img-fluid d-block mx-auto" alt="IBM" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-ibm.png'
              class='noscript noscript-img img-fluid d-block mx-auto' alt='IBM' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-indosat.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-indosat.png"
            class="lazy img-fluid d-block mx-auto" alt="Indosat Ooredoo" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-indosat.png'
              class='noscript noscript-img img-fluid d-block mx-auto' alt='Indosat Ooredoo' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-line.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-line.png"
            class="lazy img-fluid d-block mx-auto mt-2" alt="LINE" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-line.png'
              class='noscript noscript-img img-fluid d-block mx-auto mt-2' alt='LINE' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-microsoft.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-microsoft.png"
            class="lazy img-fluid d-block mx-auto mt-1" alt="Microsoft" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-microsoft.png'
              class='noscript noscript-img img-fluid d-block mx-auto mt-1' alt='Microsoft' />
          </noscript> </div>
        <div class="col-lg-3 col-sm-6 mb-5"> <img
            src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-samsung.png"
            data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-samsung.png"
            class="lazy img-fluid d-block mx-auto mt-1" alt="Samsumg" style="display: block;">
          <noscript>
            <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/home-partner-samsung.png'
              class='noscript noscript-img img-fluid d-block mx-auto mt-1' alt='Samsumg' />
          </noscript> </div>
      </div>
    </div>
  </div>
  <div class="container teaser-academy">
    <div class="row mt-5 pt-5">
      <div class="col-lg-5 ">
        <div class="mt-2"> <a href="https://www.dicoding.com/academies" class="remove-style-link"> <span
              class="text-black" style="font-weight: 500">Dicoding Academy</span> </a> </div>
        <h2 class="mb-4 mt-3">Kelas Terpopuler</h2>
        <p class="mb-lg-5 pb-lg-3">Kelas dengan peminat terbanyak di Dicoding Academy.</p>
        <div class="d-none d-lg-block">
          <p class="mt-3"> <a href="https://www.dicoding.com/academies" class="btn btn-primary shadow">Lihat Academy</a>
          </p>
        </div>
      </div>
      <div class="col-lg-7">
        <div class="row">
          <div class="col-md-6 ">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/academies/14">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_made.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_made.png"
                    class="lazy img-fluid" alt="Menjadi Android Developer Expert" style="display: block;">
                  <noscript>
                    <img src='https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_made.png'
                      class='noscript noscript-img img-fluid' alt='Menjadi Android Developer Expert' />
                  </noscript> </div>
              </a>
              <div class="m-3"> <a href="https://www.dicoding.com/academies/14">
                  <h5 data-equal-height="title" style="height: 72px;">Belajar Fundamental Aplikasi Android</h5>
                </a>
                <div>Pelajari skill Android dengan kurikulum terlengkap yang dibutuhkan oleh perusahaan. Mulai dari
                  design pattern, testing, API sampai database.</div>
                <div class="row mt-3 justify-content-end">
                  <div class="m-3 text-right"> <a href="https://www.dicoding.com/academies/14"><b>DAFTAR!</b></a> </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 ">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/academies/83">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_azure_cloud.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_azure_cloud.png"
                    class="lazy img-fluid" alt="Menjadi Azure Cloud Developer" style="display: block;">
                  <noscript>
                    <img src='https://d17ivq9b7rppb3.cloudfront.net/original/academy/academy_home_index_azure_cloud.png'
                      class='noscript noscript-img img-fluid' alt='Menjadi Azure Cloud Developer' />
                  </noscript> </div>
              </a>
              <div class="m-3"> <a href="https://www.dicoding.com/academies/83">
                  <h5 data-equal-height="title" style="height: 72px;">Menjadi Azure Cloud Developer</h5>
                </a>
                <div>Pelajari konsep dan terminologi cloud beserta berbagai layanan Azured Cloud sesuai kebutuhan
                  sertifikasi Azure Developer Associate.</div>
                <div class="row mt-3 justify-content-end">
                  <div class="m-3 text-right"> <a href="https://www.dicoding.com/academies/83"><b>DAFTAR!</b></a> </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-lg-none mt-3 mx-auto mb-5"> <a href="https://www.dicoding.com/academies/list"
          class="btn btn-primary shadow mt-3">Lihat Kelas Lainnya</a> </div>
    </div>
  </div>
  <div class="container teaser-challenge">
    <div class="row mt-5">
      <div class="col-lg-5"> <a class="remove-style-link" href="https://www.dicoding.com/challenges"> <span
            class="text-black" style="font-weight: 500">Dicoding Challenge</span> </a>
        <h2 class="mb-4 mt-3">Challenge Aktif</h2>
        <p class="mb-lg-5 pb-lg-3">Berikut adalah beberapa tantangan yang tersedia dari partner kami.</p>
        <div class="d-none d-lg-block mt-5"> <a href="https://www.dicoding.com/challenges"
            class="btn btn-primary shadow">Lihat Challenge</a> </div>
      </div>
      <div class="col-lg-7">
        <div class="row">
          <div class="col-md-6">
            <div class="card white-bg shadow mb-3"> <a href="https://www.dicoding.com/challenges/637">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20201012123518f0edb31f423ba416436982101ae7cd87.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20201012123518f0edb31f423ba416436982101ae7cd87.png"
                    class="lazy img-fluid"
                    alt="Kemenparekraf/Baparekraf Digital Challenge - Ciptakan Solusi untuk Indonesia yang Lebih Baik"
                    style="display: block;">
                  <noscript>
                    <img
                      src='https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20201012123518f0edb31f423ba416436982101ae7cd87.png'
                      class='noscript noscript-img img-fluid'
                      alt='Kemenparekraf/Baparekraf Digital Challenge - Ciptakan Solusi untuk Indonesia yang Lebih Baik' />
                  </noscript> </div>
              </a>
              <div class="card-body"> <a href="https://www.dicoding.com/challenges/637">
                  <h5 data-equal-height="title" style="height: 72px;">Kemenparekraf/Baparekraf Digital Challenge - Cip..
                  </h5>
                </a> <span class="tipe">oleh: <span class="text-muted">BaparekrafDeveloperDay</span></span> <br>
                <span>Reward: <b>1000</b> Pts &amp; <b>1000</b> XP</span> </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="card white-bg shadow mb-3"> <a href="https://www.dicoding.com/challenges/629">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20200908085639dc954a015bbb239381d2d0b773e496c9.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20200908085639dc954a015bbb239381d2d0b773e496c9.png"
                    class="lazy img-fluid"
                    alt="IDCamp 2020 Expert Developer Challenge:  Inovasi Ekonomi dan Sosial Dukung Indonesia Bangkit"
                    style="display: block;">
                  <noscript>
                    <img
                      src='https://d17ivq9b7rppb3.cloudfront.net/original/challenge/20200908085639dc954a015bbb239381d2d0b773e496c9.png'
                      class='noscript noscript-img img-fluid'
                      alt='IDCamp 2020 Expert Developer Challenge:  Inovasi Ekonomi dan Sosial Dukung Indonesia Bangkit' />
                  </noscript> </div>
              </a>
              <div class="card-body"> <a href="https://www.dicoding.com/challenges/629">
                  <h5 data-equal-height="title" style="height: 72px;">IDCamp 2020 Expert Developer Challenge: Inovasi..
                  </h5>
                </a> <span class="tipe">oleh: <span class="text-muted">idcamp</span></span> <br> <span>Reward:
                  <b>2000</b> Pts &amp; <b>2000</b> XP</span> </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-lg-none mt-3 mb-5 mx-auto"> <a href="https://www.dicoding.com/challenges/list"
          class="btn btn-primary shadow mt-3 mt-sm-0">Lihat Challenge Lainnya</a> </div>
    </div>
  </div>
  <div class="container teaser-event">
    <div class="row mt-5">
      <div class="col-lg-5">
        <div class="mt-2"> <a class="remove-style-link" href="https://www.dicoding.com/events"> <span class="text-black"
              style="font-weight: 500">Dicoding Event</span> </a> </div>
        <h2 class="mb-4 mt-3">Event Terdekat</h2>
        <p class="mb-lg-5 pb-lg-3">Kembangkan jaringan dan belajar dari developer terbaik melalui seminar/workshop yang
          difasilitasi oleh partner dan komunitas kami.</p>
        <div class="d-none d-lg-block mt-5"> <a href="https://www.dicoding.com/events"
            class="btn btn-primary shadow">Lihat Event</a> </div>
      </div>
      <div class="col-lg-7">
        <div class="row">
          <div class="col-md-6">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/events/3581">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/event/online_session_4_november_2020_belajar_dasar_pemrograman_web_logo_281020130120.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/event/online_session_4_november_2020_belajar_dasar_pemrograman_web_logo_281020130120.png"
                    class="lazy img-fluid" alt="Online Session 4 November 2020 - Belajar Dasar Pemrograman Web"
                    style="display: block;">
                  <noscript>
                    <img
                      src='https://d17ivq9b7rppb3.cloudfront.net/original/event/online_session_4_november_2020_belajar_dasar_pemrograman_web_logo_281020130120.png'
                      class='noscript noscript-img img-fluid'
                      alt='Online Session 4 November 2020 - Belajar Dasar Pemrograman Web' />
                  </noscript> </div>
              </a>
              <div class="m-4 pb-4"> <span class="badge badge-secondary mb-3">Online Discussion</span> <a
                  href="https://www.dicoding.com/events/3581">
                  <h5 data-equal-height="title" style="height: 72px;">Online Session 4 November 2020 - Belajar Dasar P..
                  </h5>
                </a> <small class="text-muted">Oleh: Dicoding Operational</small> <span
                  class="text-muted d-block mt-5 mb-2" data-toggle="tooltip" data-placement="bottom" title=""
                  data-original-title="Tanggal pelaksanaan"><i class="fas fa-calendar-alt mr-3"></i> <b>04 Nov 2020</b>
                  14:00</span> <span class="text-muted d-block mb-2" data-toggle="tooltip" data-placement="bottom"
                  title="" data-original-title="Lokasi"><i class="fas fa-map-marker-alt mr-3"></i> Online</span> </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/events/3512">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/event/dicoding_developer_coaching_8_android_membuat_tampilan_aplikasimu_semakin_menarik_dengan_style_theme_logo_261020162128.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/event/dicoding_developer_coaching_8_android_membuat_tampilan_aplikasimu_semakin_menarik_dengan_style_theme_logo_261020162128.png"
                    class="lazy img-fluid"
                    alt="Dicoding Developer Coaching #8: Android | Membuat Tampilan Aplikasimu Semakin Menarik dengan Style &amp; Theme"
                    style="display: block;">
                  <noscript>
                    <img
                      src='https://d17ivq9b7rppb3.cloudfront.net/original/event/dicoding_developer_coaching_8_android_membuat_tampilan_aplikasimu_semakin_menarik_dengan_style_theme_logo_261020162128.png'
                      class='noscript noscript-img img-fluid'
                      alt='Dicoding Developer Coaching #8: Android | Membuat Tampilan Aplikasimu Semakin Menarik dengan Style &amp; Theme' />
                  </noscript> </div>
              </a>
              <div class="m-4 pb-4"> <span class="badge badge-secondary mb-3">Seminar</span> <a
                  href="https://www.dicoding.com/events/3512">
                  <h5 data-equal-height="title" style="height: 72px;">Dicoding Developer Coaching #8: Android | Membua..
                  </h5>
                </a> <small class="text-muted">Oleh: Dicoding Event</small> <span class="text-muted d-block mt-5 mb-2"
                  data-toggle="tooltip" data-placement="bottom" title="" data-original-title="Tanggal pelaksanaan"><i
                    class="fas fa-calendar-alt mr-3"></i> <b>03 Nov 2020</b> 19:00</span> <span
                  class="text-muted d-block mb-2" data-toggle="tooltip" data-placement="bottom" title=""
                  data-original-title="Lokasi"><i class="fas fa-map-marker-alt mr-3"></i> Online</span> </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-lg-none mt-3 mb-5 mx-auto"> <a href="https://www.dicoding.com/events/list"
          class="btn btn-primary shadow ml-2">Lihat Event Lainnya</a> </div>
    </div>
  </div>
  <div class="container teaser-job">
    <div class="row mt-5 ">
      <div class="col-lg-5"> <a class="remove-style-link" href="https://www.dicoding.com/jobs"> <span class="text-black"
            style="font-weight: 500">Dicoding Job Platform</span> </a>
        <h2 class="mb-4 mt-3">Lowongan Tersedia</h2>
        <p class="mb-lg-5 pb-lg-3">Telusuri lowongan yang sesuai dengan keahlian dan minatmu.</p>
        <div class="d-none d-lg-block mt-5"> <a href="https://www.dicoding.com/jobs"
            class="btn btn-primary shadow">Lihat Job Platform</a> </div>
      </div>
      <div class="col-lg-7">
        <div class="row">
          <div class="col-md-6">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/jobs/1312">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/jobs/software_engineer_241020105339.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/jobs/software_engineer_241020105339.png"
                    class="lazy img-fluid" alt="Software Engineer" style="display: block;">
                  <noscript>
                    <img src='https://d17ivq9b7rppb3.cloudfront.net/original/jobs/software_engineer_241020105339.png'
                      class='noscript noscript-img img-fluid' alt='Software Engineer' />
                  </noscript> </div>
              </a>
              <div class="m-4 pb-4"> <span class="badge badge-secondary mb-3">Junior/Middle Programmer</span> <a
                  href="https://www.dicoding.com/jobs/1312">
                  <h5 data-equal-height="title" style="height: 72px;">Software Engineer</h5>
                </a> <small class="text-muted">Oleh: PT Rute Lintas Indonesia</small> <span class="mt-5 d-block">Terbuka
                  Hingga: <b>Nov 6, 2020</b> </span> </div>
            </div>
          </div>
          <div class="col-md-6">
            <div class="white-bg shadow rounded"> <a href="https://www.dicoding.com/jobs/1307">
                <div class="wrapper-kelas rounded-top js-balanced-height-img" style="height: 303px;"> <img
                    src="https://d17ivq9b7rppb3.cloudfront.net/original/jobs/web_developer_151020181823.png"
                    data-original="https://d17ivq9b7rppb3.cloudfront.net/original/jobs/web_developer_151020181823.png"
                    class="lazy img-fluid" alt="Web Developer" style="display: block;">
                  <noscript>
                    <img src='https://d17ivq9b7rppb3.cloudfront.net/original/jobs/web_developer_151020181823.png'
                      class='noscript noscript-img img-fluid' alt='Web Developer' />
                  </noscript> </div>
              </a>
              <div class="m-4 pb-4"> <span class="badge badge-secondary mb-3">Junior/Senior Programmer</span> <a
                  href="https://www.dicoding.com/jobs/1307">
                  <h5 data-equal-height="title" style="height: 72px;">Web Developer</h5>
                </a> <small class="text-muted">Oleh: EDUCA STUDIO</small> <span class="mt-5 d-block">Terbuka Hingga:
                  <b>Dec 31, 2020</b> </span> </div>
            </div>
          </div>
        </div>
      </div>
      <div class="d-lg-none mt-3 mb-5 mx-auto"> <a href="https://www.dicoding.com/jobs/list"
          class="btn btn-primary shadow">Lihat Lowongan Lainnya</a> </div>
    </div>
  </div>
  <div class="container-fluid cta-box p-5 mt-5">
    <div class="container text-center py-5">
      <h2><b>Bergabung Gratis Selamanya!</b></h2> <a href="https://www.dicoding.com/registration"
        class="btn btn-lg btn-primary mt-5">BUAT AKUN!</a>
    </div>
  </div>
  <div class="container-fluid success-story p-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-5 py-5 text-white">
          <h2 class="pb-3">Alumni Dicoding Academy</h2>
          <p class="mb-lg-5"> <a href="https://www.dicoding.com/academies">Dicoding Academy </a> telah memiliki 42675
            alumni yang saat ini bekerja di berbagai perusahaan teknologi atau sebagai co founder startup digital </p>
          <a href="https://www.dicoding.com/registration" class="btn btn-primary shadow">Oke, Saya Daftar!</a>
        </div>
        <div class="col-12 d-md-none">
          <div id="academyAlumnies-sm" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#academyAlumnies-sm" data-slide-to="0" class="active"></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="1" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="2" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="3" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="4" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="5" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="6" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="7" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="8" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="9" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="10" class=""></li>
              <li data-target="#academyAlumnies-sm" data-slide-to="11" class=""></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item  active ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/18176"
                              title="Danviero Yuzwan Pratama">Danviero Yuzwan Pratama</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/18176"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201905171016112843d2ce28a678a97d4799b9ed92238a.jpg"
                              class="img-graduate-profile mb-3" alt="Danviero Yuzwan Pratama"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Android Engineer at LOKET">Android Engineer at LOKET</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/danviero-yuzwan-seorang-reviewer-yang-tumbuh-bersama-dicoding/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/151533"
                              title="Alfian Yusuf Abdullah">Alfian Yusuf Abdullah</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/151533"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20191208221516c1527bd466e152e8a2e357e138fb051f.png"
                              class="img-graduate-profile mb-3" alt="Alfian Yusuf Abdullah"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Academy Code Reviewer Dicoding">Academy Code Reviewer Dicoding</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/pemuda-gorontalo-ini-tak-menyangka-bakal-kerja-di-dicoding/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/71459" title="Erma Susanti">Erma
                              Susanti</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/71459"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201803221431095625dc90accebde53a1ed2eb3664952d.png"
                              class="img-graduate-profile mb-3" alt="Erma Susanti"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Dosen yang Giat Kembangkan Diri">Dosen yang Giat Kembangkan Diri</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/erma-susanti-dosen-yang-giat-mengembangkan-diri-demi-anak-didik/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/343439"
                              title="Mohammad Nur Huda">Mohammad Nur Huda</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/343439"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20181119194548e3547d4d31a8a5ec0686ca5ae0d02c73.jpg"
                              class="img-graduate-profile mb-3" alt="Mohammad Nur Huda"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Siswa SMK Cinta Ngoding Berkat Guru">Siswa SMK Cinta Ngoding Berkat Guru</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/biar-siswa-cinta-ngoding/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/273917"
                              title="Andrew Prasetyo Herka">Andrew Prasetyo Herka</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/273917"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20180817222220ae17d1c93e9b6f577da96863b3aadee0.PNG"
                              class="img-graduate-profile mb-3" alt="Andrew Prasetyo Herka"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Karir Baru: Startup Programmer">Karir Baru: Startup Programmer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/74">Membangun Progressive Web Apps</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/karir-programmer/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/22594"
                              title="Junia Firdaus">Junia Firdaus</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/22594"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201802090728287c00858fbd2dc8556e0a1b61d5fba59c.jpg"
                              class="img-graduate-profile mb-3" alt="Junia Firdaus"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Driver Ojol jadi Android Developer">Driver Ojol jadi Android Developer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div> <a class="btn btn-sm btn-primary" href="https://www.dicoding.com/blog/junia-firdaus/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/5625"
                              title="Muh Isfhani Ghiath">Muh Isfhani Ghiath</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/5625"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20180305230827e1afdff1f70e539b16776a740f39542e.png"
                              class="img-graduate-profile mb-3" alt="Muh Isfhani Ghiath"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Engineer Tokopedia dari Sulawesi">Engineer Tokopedia dari Sulawesi</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/mahasiswa-penerima-beasiswa-google-fdp-ini-diundang-hadir-di-google-io/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/411748"
                              title="Ananda Wiradharma">Ananda Wiradharma</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/411748"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/202009011400521387fcb8e8a242a59fd98b151578374d.png"
                              class="img-graduate-profile mb-3" alt="Ananda Wiradharma"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Karyawan Pabrik Lulus Google AAD">Karyawan Pabrik Lulus Google AAD</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/android-developer-tembus-google-aad/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/58371"
                              title="Angga Pratama">Angga Pratama</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/58371"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20200824005413b31270388616a113d7ad6f9378bfa2b9.png"
                              class="img-graduate-profile mb-3" alt="Angga Pratama"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Lulusan Biologi jadi Android Dev">Lulusan Biologi jadi Android Dev</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/lulusan-tercepat-kelas-kade-ini-ternyata/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/189872" title="Rui Fernando">Rui
                              Fernando</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/189872"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201910181621080031893412d6af8265f2929c93faa81d.png"
                              class="img-graduate-profile mb-3" alt="Rui Fernando"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Direkrut Unicorn Sejak Masih Kuliah">Direkrut Unicorn Sejak Masih Kuliah</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/masih-kuliah-sudah-keterima-kerja-di-unicorn/">Lihat
                        Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/8007"
                              title="Rizqi Aryansa">Rizqi Aryansa</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/8007"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20190117154924ffd921f0b68628e6f1b1c7110bdbaced.jpg"
                              class="img-graduate-profile mb-3" alt="Rizqi Aryansa"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Engineer Tokopedia &amp; Reviewer">Engineer Tokopedia &amp; Reviewer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/3-tips-belajar-agar-siap-kerja-di-unicorn/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item ">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/221778"
                              title="Emrycho C J Simanungkalit">Emrycho C J Simanungkalit</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/221778"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/202005210945476a116f31739b3392fc3a2aed914bdbed.png"
                              class="img-graduate-profile mb-3" alt="Emrycho C J Simanungkalit"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Anak Desa jadi Engineer Gojek">Anak Desa jadi Engineer Gojek</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/74">Membangun Progressive Web Apps</a></span>
                      </div> <a class="btn btn-sm btn-primary"
                        href="https://www.dicoding.com/blog/tips-dapat-tawaran-kerja-di-unicorn/">Lihat Cerita</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-7 d-none d-md-block">
          <div id="academyAlumnies" class="carousel slide" data-ride="carousel">
            <ol class="carousel-indicators">
              <li data-target="#academyAlumnies" data-slide-to="0" class="active"></li>
              <li data-target="#academyAlumnies" data-slide-to="1" class=""></li>
              <li data-target="#academyAlumnies" data-slide-to="2" class=""></li>
            </ol>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/18176"
                              title="Danviero Yuzwan Pratama">Danviero Yuzwan Pratama</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/18176"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201905171016112843d2ce28a678a97d4799b9ed92238a.jpg"
                              class="img-graduate-profile mb-3" alt="Danviero Yuzwan Pratama"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Android Engineer at LOKET">Android Engineer at LOKET</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/danviero-yuzwan-seorang-reviewer-yang-tumbuh-bersama-dicoding/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/151533"
                              title="Alfian Yusuf Abdullah">Alfian Yusuf Abdullah</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/151533"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20191208221516c1527bd466e152e8a2e357e138fb051f.png"
                              class="img-graduate-profile mb-3" alt="Alfian Yusuf Abdullah"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Academy Code Reviewer Dicoding">Academy Code Reviewer Dicoding</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/pemuda-gorontalo-ini-tak-menyangka-bakal-kerja-di-dicoding/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/71459" title="Erma Susanti">Erma
                              Susanti</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/71459"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201803221431095625dc90accebde53a1ed2eb3664952d.png"
                              class="img-graduate-profile mb-3" alt="Erma Susanti"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Dosen yang Giat Kembangkan Diri">Dosen yang Giat Kembangkan Diri</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/erma-susanti-dosen-yang-giat-mengembangkan-diri-demi-anak-didik/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/343439"
                              title="Mohammad Nur Huda">Mohammad Nur Huda</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/343439"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20181119194548e3547d4d31a8a5ec0686ca5ae0d02c73.jpg"
                              class="img-graduate-profile mb-3" alt="Mohammad Nur Huda"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Siswa SMK Cinta Ngoding Berkat Guru">Siswa SMK Cinta Ngoding Berkat Guru</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/biar-siswa-cinta-ngoding/" target="_blank">Lihat
                          Cerita</a> </p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/273917"
                              title="Andrew Prasetyo Herka">Andrew Prasetyo Herka</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/273917"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20180817222220ae17d1c93e9b6f577da96863b3aadee0.PNG"
                              class="img-graduate-profile mb-3" alt="Andrew Prasetyo Herka"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Karir Baru: Startup Programmer">Karir Baru: Startup Programmer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/74">Membangun Progressive Web Apps</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/karir-programmer/" target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/22594"
                              title="Junia Firdaus">Junia Firdaus</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/22594"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201802090728287c00858fbd2dc8556e0a1b61d5fba59c.jpg"
                              class="img-graduate-profile mb-3" alt="Junia Firdaus"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Driver Ojol jadi Android Developer">Driver Ojol jadi Android Developer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/junia-firdaus/" target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/5625"
                              title="Muh Isfhani Ghiath">Muh Isfhani Ghiath</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/5625"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20180305230827e1afdff1f70e539b16776a740f39542e.png"
                              class="img-graduate-profile mb-3" alt="Muh Isfhani Ghiath"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Engineer Tokopedia dari Sulawesi">Engineer Tokopedia dari Sulawesi</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/mahasiswa-penerima-beasiswa-google-fdp-ini-diundang-hadir-di-google-io/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/411748"
                              title="Ananda Wiradharma">Ananda Wiradharma</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/411748"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/202009011400521387fcb8e8a242a59fd98b151578374d.png"
                              class="img-graduate-profile mb-3" alt="Ananda Wiradharma"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Karyawan Pabrik Lulus Google AAD">Karyawan Pabrik Lulus Google AAD</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/14">Belajar Fundamental Aplikasi Android</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/android-developer-tembus-google-aad/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                </div>
              </div>
              <div class="carousel-item">
                <div class="row pb-5">
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/58371"
                              title="Angga Pratama">Angga Pratama</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/58371"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20200824005413b31270388616a113d7ad6f9378bfa2b9.png"
                              class="img-graduate-profile mb-3" alt="Angga Pratama"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Lulusan Biologi jadi Android Dev">Lulusan Biologi jadi Android Dev</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/lulusan-tercepat-kelas-kade-ini-ternyata/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/189872" title="Rui Fernando">Rui
                              Fernando</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/189872"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/201910181621080031893412d6af8265f2929c93faa81d.png"
                              class="img-graduate-profile mb-3" alt="Rui Fernando"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Direkrut Unicorn Sejak Masih Kuliah">Direkrut Unicorn Sejak Masih Kuliah</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/masih-kuliah-sudah-keterima-kerja-di-unicorn/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/8007"
                              title="Rizqi Aryansa">Rizqi Aryansa</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/8007"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/20190117154924ffd921f0b68628e6f1b1c7110bdbaced.jpg"
                              class="img-graduate-profile mb-3" alt="Rizqi Aryansa"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Engineer Tokopedia &amp; Reviewer">Engineer Tokopedia &amp; Reviewer</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/129">Belajar Android Jetpack Pro</a></span> </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/3-tips-belajar-agar-siap-kerja-di-unicorn/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                  <div class="col-md-6">
                    <div class="white-bg shadow rounded p-3 my-2" data-equal-height="alumni-card"
                      style="height: 195px;">
                      <div class="row mb-2">
                        <div class="order-1 order-xl-0 col-xl-8">
                          <h5><a class="text-dark" href="https://www.dicoding.com/users/221778"
                              title="Emrycho C J Simanungkalit">Emrycho C J Simanungkalit</a></h5>
                        </div>
                        <div class="order-0 order-xl-1 col-xl-4"> <a href="https://www.dicoding.com/users/221778"> <img
                              src="https://d17ivq9b7rppb3.cloudfront.net/small/avatar/202005210945476a116f31739b3392fc3a2aed914bdbed.png"
                              class="img-graduate-profile mb-3" alt="Emrycho C J Simanungkalit"> </a> </div>
                      </div>
                      <div data-equal-height="company" style="height: 24px;"> <span class="text-muted d-block ellipsis"
                          title="Anak Desa jadi Engineer Gojek">Anak Desa jadi Engineer Gojek</span> </div>
                      <div data-equal-height="graduate" style="height: 24px;"> <span class="tipe">Lulusan Kelas <a
                            href="https://www.dicoding.com/academies/74">Membangun Progressive Web Apps</a></span>
                      </div>
                      <p class="mb-0 mt-2"> <a class="btn w-100 btn-sm btn-primary"
                          href="https://www.dicoding.com/blog/tips-dapat-tawaran-kerja-di-unicorn/"
                          target="_blank">Lihat Cerita</a> </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container footer-commons">
    <div class="row py-5">
      <div class="col-sm-6 col-md-3 order-sm-0 order-md-0"> <img
          src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/certificate_logo.png" alt="Dicoding Logo"
          style="max-height: 37px;"> <br> <img
          src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/aba-2019-2.png"
          data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/aba-2019-2.png"
          class="lazy aba mt-3 mr-3" alt="Asean Business Award 2019" style="display: inline;">
        <noscript>
          <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/aba-2019-2.png'
            class='noscript noscript-img aba mt-3 mr-3' alt='Asean Business Award 2019' />
        </noscript> <img src="https://d17ivq9b7rppb3.cloudfront.net/original/commons/afwc-2.svg"
          data-original="https://d17ivq9b7rppb3.cloudfront.net/original/commons/afwc-2.svg" class="lazy afwc mt-3"
          alt="Asean Future Workforce Council" style="display: inline;">
        <noscript>
          <img src='https://d17ivq9b7rppb3.cloudfront.net/original/commons/afwc-2.svg'
            class='noscript noscript-img afwc mt-3' alt='Asean Future Workforce Council' />
        </noscript> </div>
      <div class="col-sm-12 col-md-6 order-sm-2 order-md-1">
        <div class="row">
          <div class="col-sm-4 mt-3 mt-md-0">
            <dl>
              <dt class="text-muted">PERUSAHAAN</dt>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/about">Tentang Kami</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/blog">Blog</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/feeds">Berita Terbaru</a></dd>
              <dd> <a href="https://www.facebook.com/dicoding" class="social-media-link p-1 p-md-0 mr-2 text-muted"><i
                    class="fab fa-facebook-square"></i></a> <a href="https://www.instagram.com/dicoding"
                  class="social-media-link p-1 p-md-0 mr-2 text-muted"><i class="fab fa-instagram"></i></a> <a
                  href="https://twitter.com/dicoding" class="social-media-link p-1 p-md-0 mr-2 text-muted"><i
                    class="fab fa-twitter"></i></a> <a href="https://www.youtube.com/channel/UCM6BWkgiGrCHG967i_PyMiw"
                  class="social-media-link p-1 p-md-0 mr-2 text-muted"><i class="fab fa-youtube"></i></a> </dd>
            </dl>
          </div>
          <div class="col-sm-4 mt-3 mt-md-0">
            <dl>
              <dt class="text-muted">PROGRAM</dt>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/academies">Academy</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/challenges">Challenge</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/events">Event</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/jobs">Job</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/rewards">Rewards</a></dd>
            </dl>
          </div>
          <div class="col-sm-4 mt-3 mt-md-0">
            <dl>
              <dt class="text-muted">SUPPORT</dt>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://help.dicoding.com/">Bantuan</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/faq">FAQ</a></dd>
              <dd><a class="d-inline-block py-2 py-md-1" href="https://www.dicoding.com/consultation">Hubungi Kami</a>
              </dd>
              <dd> <a href="https://www.facebook.com/dicoding" class="social-media-link p-1 p-md-0 mr-2 text-muted"><i
                    class="fab fa-facebook-square"></i></a> <a href="https://www.instagram.com/dicoding"
                  class="social-media-link p-1 p-md-0 mr-2 text-muted"><i class="fab fa-instagram"></i></a> <a
                  href="https://twitter.com/dicoding" class="social-media-link p-1 p-md-0 mr-2 text-muted"><i
                    class="fab fa-twitter"></i></a> <a href="https://www.youtube.com/channel/UCM6BWkgiGrCHG967i_PyMiw"
                  class="social-media-link p-1 p-md-0 mr-2 text-muted"><i class="fab fa-youtube"></i></a> </dd>
            </dl>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="container-fluid gray-bg border-top">
    <div class="container">
      <div class="row py-3">
        <div class="col-sm-6"><small>Copyright © 2020 - Sirojudin Munir. All rights reserved.</small></div>
        <div class="col-sm-6 text-right"><a href="https://www.dicoding.com/termsofuse" class="mr-4">Terms</a> <a
            href="https://www.dicoding.com/privacy">Privacy</a></div>
      </div>
    </div>
  </div>

  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
    integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
    integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
    crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.min.js"
    integrity="sha384-w1Q4orYjBQndcko6MimVbzY0tgp4pWB4lZ7lr30WKz0vr/aWKhXdBNmNb5D92v7s"
    crossorigin="anonymous"></script>
  <script>
    $(window).scroll(function () {
      var scroll = $(window).scrollTop();
      if (scroll < 300) {
        $(".sticky-top").css("background", "transparent");
        $(".sticky-top").css("z-index", "1000");
        $(".sticky-top").css(
          "box-shadow",
          "none"
        );
        $(".nav-link").removeClass("dark");
      } else {
        $(".sticky-top").css("background", "white");
        $(".sticky-top").css(
          "box-shadow",
          "rgba(0, 0, 0, 0.12) 0px 2px 4px 0px"
        );
        $(".nav-link").addClass("dark");
      }
    });
  </script>
</body>

</html>
