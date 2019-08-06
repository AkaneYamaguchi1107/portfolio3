<template>
  <div>
    <header class="header">
      <h1 class="header__title">flower</h1>
      <ul class="gnav">
        <li class="gnav__item">
          <nuxt-link to="" class="gnav__link">Topics</nuxt-link>
        </li>
        <li class="gnav__item">
          <nuxt-link to="" class="gnav__link">Gift</nuxt-link>
        </li>
        <li class="gnav__item">
          <nuxt-link to="" class="gnav__link">Message</nuxt-link>
        </li>
      </ul>
    </header>
    <nuxt />
    <footer class="footer">
      <h1 class="footer__title">flower</h1>
      <ul class="fnav">
        <li class="fnav__item">
          <nuxt-link to="" class="fnav__link">Topics</nuxt-link>
        </li>
        <li class="fnav__item">
          <nuxt-link to="" class="fnav__link">Gift</nuxt-link>
        </li>
        <li class="fnav__item">
          <nuxt-link to="" class="fnav__link">Message</nuxt-link>
        </li>
      </ul>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
.header {
  padding: 0 16px;
  line-height: 56px;
  font-size: 32px;
  display: flex;
  justify-content: space-between;
}
.gnav {
  display: flex;
  // padding-right: 40px;
  &__item {
    font-size: 24px;
    padding-right: 40px;
  }
}
.footer {
  padding: 0 16px;
  display: flex;
  justify-content: space-between;
  &__title {
    font-size: 16px;
  }
}
.fnav {
  display: flex;
  // justify-content: space-between;
  &__item {
    padding-right: 40px;
  }
}
</style>
