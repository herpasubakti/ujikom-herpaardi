<template>
  <nav class="navbar navbar-expand-lg fixed-top navbar-scroll">
    <div class="container">
      <img src="assets/LOGO-SMK4.png" height="90" alt="" loading="lazy" />
      <div class="col ms-5">
        <h5>SMKN 4 TASIKMALAYA</h5>
        <h6>JL.Depok Kel. Sukamenak Kec.purbaratuKota Kota.Tasikmalaya</h6>
      </div>
      <button class="navbar-toggler ps-0" type="button" data-mdb-toggle="collapse" data-mdb-target="#navbarExample01" aria-controls="navbarExample01" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon d-flex justify-content-start align-items-center">
          <i class="fas fa-bars"></i>
        </span>
      </button>
      <div class="collapse navbar-collapse" id="navbarExample01">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item active">
            <nuxt-link to="/">
              <a class="nav-link" aria-current="page">BERANDA</a>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/profil">
              <a class="nav-link" aria-current="page">PROFIL</a>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/galeri">
              <a class="nav-link" aria-current="page">GELERI</a>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/eskul">
              <a class="nav-link" aria-current="page">EKTRAKULIKULER</a>
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link to="/biodata">
              <a class="nav-link" aria-current="page">BIODATA</a>
            </nuxt-link>
          </li>
        </ul>

        <ul class="navbar-nav flex-row">
          <li class="nav-item">
            <a class="nav-link px-2" href="#!">
              <i class="fab fa-facebook-square"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link px-2" href="#!">
              <i class="fab fa-instagram"></i>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link ps-2" href="#!">
              <i class="fab fa-youtube"></i>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style scoped>
/* Color of the links BEFORE scroll */
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
</style>
