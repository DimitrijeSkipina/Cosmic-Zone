<template>
  <header class="header">
    <div class="header__content">
      <div>LOGO</div>
      <div class="header__nav">
        <router-link class="header__nav-link" to="/">Home</router-link>
        <router-link class="header__nav-link" to="/about">About</router-link>
      </div>
      <div class="header__right">Login</div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 53px;
  background-color: bisque;
  display: flex;
  justify-content: center;
  align-items: center;
  &__content {
    width: 1200px;
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid #46a358;
  }
  &__logo {
    color: #46a358;
  }
  &__nav {
    display: flex;
    gap: 50px;
    &-link {
      font-weight: 700;
      font-size: 16px;
      color: #3d3d3d;
    }
  }
  &__rigth {
    display: flex;
    gap: 50px;
  }
}
</style>
