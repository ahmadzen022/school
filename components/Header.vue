<!-- <template>
  <div class="container">
    <nav class="navbar navbar-expand-lg fixed-top navbar-scroll">
      <div class="container">
        <img src="/assets/img/LogoSMKN4.png" height="70" alt="" loading="lazy" />
        <h3 class="mx-3">SMKN4</h3>
        <button class="navbar-toggler ps-0" type="button" data-mdb-toggle="collapse" data-mdb-target="#navbarExample01" aria-controls="navbarExample01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon d-flex justify-content-start align-items-center">
            <i class="fas fa-bars"></i>
          </span>
        </button>
        <div class="collapse navbar-collapse" id="navbarExample01">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item active">
              <a class="nav-link" aria-current="page" href="#Home">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#Sejarah">Sejarah</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#VisiMisi">Visi Misi</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#adoptions">Ekstrakurikuler</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#Jurusan">Jurusan</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#education">Education</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#about">About us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#contact">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<style>
.navbar-scroll .nav-link,
.navbar-scroll .fa-bars,
.navbar-scroll .navar-brand {
  color: #4f4f4f;
}

.navbar-scroll .nav-link:hover {
  color: #1266f1;
}

/* Color of the links AFTER scroll */
.navbar-scrolled .nav-link,
.navbar-scrolled .fa-bars,
.navbar-scrolled .navar-brand {
  color: #4f4f4f;
}

/* Color of the navbar AFTER scroll */
.navbar-scroll,
.navbar-scrolled {
  background-color: #fff;
}

/* An optional height of the navbar AFTER scroll */
.navbar.navbar-scroll.navbar-scrolled {
  padding-top: 5px;
  padding-bottom: 5px;
}

body {
  background-color: #eee;
}
</style> -->
<template>
  <div>
    <!-- Hero Section -->
    <section id="hero">
      <!-- Navbar -->
      <nav class="navbar navbar-expand-lg navbar-light bg-transparent position-fixed w-100">
        <div class="container">
          <a class="navbar-brand" href="#hero">
            <img src="assets/img/LogoSMKN4.png" alt="" width="34" class="d-inline-block align-text-top me-3" />
            SMKN4 KOTA TASIKMALAYA
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav mx-auto">
              <li class="nav-item mx-2">
                <a class="nav-link active" aria-current="page" href="#hero">Beranda</a>
              </li>
              <li class="nav-item mx-2">
                <a class="nav-link" href="#layanan">Layanan</a>
              </li>
              <li class="nav-item mx-2">
                <a class="nav-link" href="#fitur">Fitur</a>
              </li>
              <li class="nav-item mx-2">
                <a class="nav-link" href="#kontak">Kontak</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

      <!-- Tagline -->
      <div class="container h-100">
        <div class="row h-100">
          <div class="col-lg-6 col-sm-12 hero-tagline my-auto">
            <h1>Membantu Temukan Rumah Impian.</h1>
            <p><span class="fw-bold">Rumah Impian </span>hadir untuk Temukan rumah terbaik untukmu, untuk dijual ataupun disewa dengan sumber terpecaya.</p>
            <button class="button-lg-secondary me-4">Temukan Rumah</button>
            <a href="#rekomendasi">
              <img src="assets/img/Right Arrow.png" alt="" />
            </a>
          </div>
        </div>
        <img src="assets/img/Hero Image.png" class="image-hero position-absolute end-0 bottom-0" alt="" />
        <img src="assets/img/Accsent 1.png" alt="" class="h-100 position-absolute top-0 start-0 accsent-img" />
      </div>
    </section>
    <!-- End navbar -->
  </div>
</template>

<style>
:root {
  --pr-color: #048853;
}

body {
  font-family: "Poppins", sans-serif;
  background-color: #f3fff4;
}
/* Nav Fixed on Scroll */

.nav-color {
  background-color: #005a36;
}

/* Nav Scroll */

.navbar {
  z-index: 3;
}

nav .navbar-brand {
  font-size: 20px;
  font-weight: 700;
  color: #fff !important;
}

.navbar .nav-link.active {
  font-weight: 700;
}

.nav-link:hover {
  background-color: var(--pr-color);
}

.navbar .nav-link {
  font-size: 1rem;
  color: #fff !important;
}

.button-primary {
  width: 133px;
  height: 40px;
  background-color: transparent;
  border: 1px solid rgba(255, 255, 255, 0.3);
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
}

.button-secondary {
  width: 133px;
  height: 40px;
  background-color: #fff;
  color: var(--pr-color);
  font-size: 1rem;
  font-weight: 500;
  border: none;
}

.button-lg-secondary {
  width: 237px;
  height: 70px;
  background-color: #fff;
  color: var(--pr-color);
  border: none;
  font-size: 20px;
  font-weight: 700;
}

/* Hero Section */

#hero {
  background: linear-gradient(160deg, var(--pr-color), #000);
  height: 100vh;
  width: 100%;
}

#hero img {
  z-index: 0;
}

.image-hero {
  height: 100%;
}

.hero-tagline h1 {
  font-size: 50px;
  color: #fff;
  line-height: 72px;
}

.hero-tagline p {
  font-size: 1rem;
  color: #fff;
  margin-bottom: 60px;
  margin-top: 20px;
  line-height: 30px;
  width: 90%;
}

* {
  z-index: 2;
}

.accsent-img {
  z-index: 1;
}

/* Layanan */

#layanan,
#rekomendasi {
  padding: 100px 0;
}

h2 {
  font-size: 48px;
  color: var(--pr-color);
}

.sub-title {
  font-size: 18px;
  color: #000;
}

.card-layanan {
  width: 100%;
  height: 313px;
  border-radius: 5px;
  padding: 40px;
  box-shadow: 0 0 7px 3px rgba(0, 0, 0, 0.055);

  transition: all 0.3s ease-in;
}

.circle-icon {
  width: 70px;
  height: 70px;
  background-color: var(--pr-color);
  border-radius: 50%;

  transition: all 0.1s ease-in;
}

.card-layanan h3 {
  color: #000;
  font-size: 24px;

  transition: all 0.2s ease-in;
}

.card-layanan p {
  color: #000;
  font-size: 14px;

  transition: all 0.3s ease-in;
}

.card-layanan:hover {
  width: 100%;
  height: 313px;
  background: linear-gradient(var(--pr-color), #002e1b);
  border-radius: 5px;
  padding: 40px;

  transition: all 0.3s ease-in;
}

.card-layanan:hover h3 {
  color: #fff;
  font-size: 24px;

  transition: all 0.2s ease-in;
}

.card-layanan:hover p {
  color: #fff;
  font-size: 14px;

  transition: all 0.3s ease-in;
}

.card-layanan:hover .circle-icon img {
  transform: scale(2);
}

.card-layanan:hover .circle-icon {
  background-color: #fff;
  transform: scale(1.1);

  transition: all 0.4s ease-in;
}

/* Section Cari */

#cari {
  height: 100vh;
  background-image: url(../Assets/Img-search.png);
  background-repeat: no-repeat;
  background-size: cover;
}

#cari h2 {
  font-size: 52px;
  color: #fff;
  font-weight: 500;
}

#cari p {
  color: #fff;
  font-size: 24px;
  font-weight: 300;
  width: 70%;
}

.input-cari {
  height: 80px;
}

.input-cari:focus {
  border: none;
}

.input-cari .button-secondary {
  width: 200px;
  height: 88px;
  background-color: rgba(255, 255, 255, 0.8);
  color: var(--pr-color);
  font-size: 1rem;
  font-weight: 500;
  border: none;
}

.input-cari .button-primary {
  height: 88px;
  background-color: var(--pr-color);
  color: #fff;
  border: none;
  font-size: 27px;
  font-weight: 500;
  border-radius: 0 10px 0 10px;
  /* border : none; */
}

.nav-tabs {
  border: none;
}

.nav-tabs .nav-link {
  background-color: rgba(255, 255, 255, 0.5);
  border-radius: 0 0 0 0;
}

.nav-tabs .nav-link {
  color: #000;
  border: none;
}

.nav-link:hover {
  border: none;
}

.nav-tabs .nav-link.active {
  background-color: rgba(255, 255, 255, 0.8);
  color: var(--pr-color);
  border-radius: 0 9px 0 0;
  font-weight: 500;
}

.card {
  height: 440px;
  border: none;
}

.card-body h4 {
  color: #454545;
  font-weight: 600;
  font-size: 24px;
  line-height: 0.8rem;
}

.card-body p {
  color: #454545;
  font-weight: 400;
  font-size: 14px;
}

.card-fasilitas {
  position: absolute;
  right: 0;
  left: 0;
  bottom: 10px;
  background-color: #fff;
}

.card-fasilitas span {
  font-weight: 500;
  margin-top: 18px;
  color: #454545;
}

.card-fasilitas span p {
  font-size: 12px;
  color: #454545;
}

.card:hover {
  background: linear-gradient(170deg, var(--pr-color), #007245, #007245, #000);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.25);
  border: none;
  transition: all ease-in-out 0.3s;
}

.card:hover .card-body h4 {
  color: #fff;
  transition: all ease-in-out 0.3s;
}

.card:hover .card-body p {
  color: #fff;
  transition: all ease-in-out 0.3s;
}

.card:hover .card-fasilitas p {
  color: #000;
}

.button-fitur {
  width: 241px;
  height: 63px;
  background-color: var(--pr-color);
  border: none;
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
}

.button-arrow-left {
  border: none;
  border-radius: 50%;
  width: 70px;
  height: 70px;
  background-color: var(--pr-color);
  padding: 0;
}

.button-arrow-right {
  border: none;
  border-radius: 50%;
  width: 70px;
  height: 70px;
  background-color: var(--pr-color);
  padding: 0;
}

.card-fitur .overlay {
  background-color: rgba(0, 0, 0, 0);
  opacity: 0;
  transition: all 0.3s ease-in-out;
}
.card-fitur .overlay:hover {
  background-color: rgba(0, 0, 0, 0.6);
  opacity: 1;
}

.fitur-detail h5 {
  color: #fff;
  font-size: 32px;
  font-weight: 600;
}

.fitur-detail span {
  color: #fff;
  font-size: 14px;
}

.fitur-detail h6 {
  color: #fff;
  font-size: 24px;
  font-weight: 600;
}

.fitur-detail button {
  width: 150px;
  height: 45px;
  background-color: var(--pr-color);
  border: none;
  font-size: 1rem;
  font-weight: 500;
  color: #fff;
}
#kontak {
  background-image: url(../Assets/kontak-img.png);
  background-size: cover;
  background-repeat: no-repeat;
  margin-top: 160px;
}
#kontak h3 {
  width: 70%;
  font-size: 40px;
  color: #fff;
}

#kontak .overlay {
  background-color: rgba(0, 0, 0, 0.5);
}

#kontak .container {
  padding: 130px 0;
}

.card-contact {
  height: 445px;
  background-color: #fff;
  border-radius: 5px;
  padding: 75px 48px;
}

.card-contact .form-control {
  height: 75px;
  border-radius: 0;
  background-color: #dadada;
}

.card-contact .form-control:focus {
  box-shadow: 0 0 3px var(--pr-color);
}

.card-contact label {
  color: #656565;
  font-size: 18px;
}

.button-kontak {
  width: 100%;
  height: 75px;
  background-color: var(--pr-color);
  border: none;
  font-size: 23px;
  font-weight: 600;
  color: #fff;
}

.kontak h6 {
  color: #fff;
}

.kontak a {
  color: #fff;
  width: 355px;
  font-size: 16px;
  text-decoration: none;
}

footer .container-fluid {
  height: 267px;
  background-color: #000000;
}

footer a {
  text-decoration: none;
  color: #fff;
  font-size: 18px;
  font-weight: 600;
}

footer p {
  font-size: 14px;
  color: #fff;
}
</style>
