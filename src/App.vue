<template>
  <div id="app">
    <div id="nav">
      <div>
        <b-navbar class="container" toggleable="lg" type="dark">
          <b-navbar-brand href="#">logo</b-navbar-brand>

          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto">
              <b-navbar-nav>
                <b-nav-item href="#">Home</b-nav-item>
                <b-nav-item href="#">Layanan</b-nav-item>
                <b-nav-item href="#">Kontak</b-nav-item>
                <b-nav-item href="#">Tentang</b-nav-item>
              </b-navbar-nav>
              <b-nav-form>
                <b-button size="sm" class="my-2 my-sm-0" type="submit">Join Us</b-button>
              </b-nav-form>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style lang="stylus">
  @import url('https://fonts.googleapis.com/css?family=Saira+Semi+Condensed&display=swap');
  @import url('https://fonts.googleapis.com/css?family=Dosis&display=swap');

  .navbar-dark .navbar-brand {
    text-transform : uppercase;
    color : #fff;
    font-family: 'Saira Semi Condensed', sans-serif;
  }
  .navbar-dark .navbar-nav .nav-link {
    text-transform : uppercase;
    color : #000;
    font-family: 'Saira Semi Condensed', sans-serif;
  }
  .navbar-dark .navbar-nav .btn {
    text-transform : uppercase;
    background-color: #FFCD63;
    color: #000;
  }

  /* DESKTOP VERSION */
  @media (min-width: 992px) {
    .navbar-dark .navbar-brand {
      color : #fff;
    }
    .navbar-dark .navbar-nav .nav-link {
      color : #fff;
    }
  }
</style>
