<template>
  <div>
    <b-jumbotron>
      <!-- <b-img src="../assets/tes.png" fluid alt="Fluid image"></b-img> -->
      <div class="container d-flex h-100">
      <div class="row justify-content-center align-self-center">
        <div class="col-md-6 intro-info order-md-first order-last">
          <h2>Solusi<br>Untuk Bisnis <span>Anda</span></h2>
          <div>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim. sed do eiusmod tempor incididunt.</p>
            <b-button>Get Started</b-button>
          </div>
        </div>
  
        <div class="col-md-6 intro-img order-md-last order-first">
          <img src="../assets/tes3.png" alt="" class="img-fluid">
        </div>
      </div>

    </div>
    </b-jumbotron>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'Home',
  components: {}
}
</script>

<style lang="stylus" scoped>
  .jumbotron {
    background-image: linear-gradient(to top, #0c3483 0%, #a2b6df 100%, #6b8cce 100%, #a2b6df 100%);
    background-size: cover;
    border-radius: 0;
    height: 640px;
    margin-top: -60px;
  }
  .jumbotron h2 {
    font-family: 'Dosis', sans-serif;
    color: #fff;
  }
  .jumbotron p {
    color : #ffffff;
  }
  .jumbotron button {
    display: inline-block;
    background: rgba(255, 255, 255, .10);
    color: #fff;
    font-family: $rob;
    width: 134px;
    font-size: 14px;
    font-weight: 500;
    border: 1px solid rgba(255, 255, 255, .50);
    line-height: 48px;
    border-radius: 3px;
    outline: none !important;
    box-shadow: none !important;
    text-align: center;
    cursor: pointer;
    @include transition;
    &:hover{
      background: #fff;
      color: #000;
      border-color: #fff;
    }
  }
  
  /* DESKTOP VERSION */
  @media (min-width: 992px) {
    .jumbotron {
      margin-top: -75px;
    }
  }
</style>
