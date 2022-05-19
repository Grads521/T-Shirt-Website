<template>
  <header class="header">
    <div class="header__left">
      <router-link to="/" class="header__logo">mangcoding Store</router-link>
    </div>
    <!-- <nav class="header__nav">
      <ul class="header__link">
        <li><a href="">Home</a></li>
        <li><a href="">Shop</a></li>
        <li><a href="">About Us</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </nav>
    <div class="header__icons">
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
    </div>
    <div class="header__input">

    </div> -->
  </header>
  
  <!-- <footer class="footer">
    <h1>Footer</h1>
  </footer> -->
</template>

<script>
</script>

<style lang="scss">
@import './css/variables.scss';

body {
  max-width: 1440px;
  margin: 0 auto;
}

.header {
  display: flex;
  justify-content: space-between;
  max-height: 80px;
  background-color: bisque;
  
  &__left {
    padding: 23px 0;
  }
  
  &__logo {
    display: inline-block;
    font-family: 'Roboto', sans-serif;
    font-size: 14px;
    color: $dark;
    padding-left: 44px;
    margin: 9px 0;
    max-height: 34px;
    background: url('./assets/img/header/Logo.png') no-repeat;
  }
}

</style>
