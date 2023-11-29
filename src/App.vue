<template>
  <div id="app">
    <div>
      <b-navbar toggleable="lg" type="dark" fixed="top">
        <b-container>
          <!--b-navbar-toggle target="nav-collapse"></b-navbar-toggle-->

          <b-img :src="require('@/assets/firma.png')" class="logo mx-auto" alt="Responsive image"></b-img>
          <!--b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="mx-auto">
              <b-nav-item href="#">Home</b-nav-item>
              <b-nav-item href="#">About</b-nav-item>
              <b-nav-item href="#">Photogallery</b-nav-item>
            </b-navbar-nav>
          </b-collapse-->
        </b-container>
      </b-navbar>

      <b-img src="https://drive.google.com/uc?id=1FoQz-9kogtazX7AmMIyXiYPNhoMbQyAo" class="background-img" alt="Responsive image"></b-img>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
.logo {
  width: 70px;
}
.background-img {
  width: 100%;
  height: 100vh;
  object-fit: cover;
}
</style>