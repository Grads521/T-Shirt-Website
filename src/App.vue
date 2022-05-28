<template>
  <header class="header">
    <div class="header__left">
      <router-link to="/" class="header__logo">mangcoding Store</router-link>
    </div>
    <nav class="header__nav">
      <router-link to="/" class="header__link active">
        <span>Home</span>
      </router-link>
      <router-link to="/shop" class="header__link">
        <span>Shop</span>
      </router-link>
      <router-link to="/about" class="header__link">
        <span>About Us</span>
      </router-link>
      <router-link to="/contact" class="header__link">
        <span>Contact</span>
      </router-link>
    </nav>
    <div class="header__icons">
      <img src="" alt="">
      <img src="" alt="">
      <img src="" alt="">
    </div>
    <div class="header__input">

    </div>
  </header>

  <router-view>
    
  </router-view>
  
  <!-- <footer class="footer">
    <h1>Footer</h1>
  </footer> -->
</template>

<script>
</script>

<style lang="scss">
@import './css/variables.scss';

body {
  max-width: 1180px;
  margin: 0 auto;
}

.header {
  display: flex;
  justify-content: space-between;
  max-height: 80px;
  background-color: bisque;
  
  &__left {
    margin: 23px 0;
  }
  
  &__logo {
    display: inline-block;
    font-family: 'Roboto', sans-serif;
    font-size: 14px;
    color: $dark;
    padding: 9px 0 9px 44px;
    max-height: 34px;
    background: url('./assets/img/header/Logo.png') no-repeat left center;
  }
  &__nav {
    margin: 30px;
  }
  &__link {
    font-family: 'Mada', sans-serif;
    font-weight: 400;
    font-size: 18px;
    margin-right: 30px;
    padding: 10px;
    &:last-child {
      margin: 0px;
    }
  }
}

</style>
