<template>
  <div>
    <header class="header">
      <p class="header__logo">
        ポートフォリオ
      </p>
      <ul class="gnav">
        <li class="gnav__item">
          <a href="#profile" class="gnav__link">プロフィール</a>
        </li>
      </ul>
      <ul class="gnav">
        <li class="gnav__item">
          <a href="#skill" class="gnav__link">スキルセット</a>
        </li>
      </ul>
      <ul class="gnav">
        <li class="gnav__item">
          <a href="" class="gnav__link">仕事の相談</a>
        </li>
      </ul>
    </header>
    <nuxt />
    <footer class="footer">
      <ul class="footer-nav">
        <li class="footer-nav__item">
          <a href="#profile" class="footer-nav__link">プロフィール</a>
        </li>
        <li class="footer-nav__item">
          <a href="#skill" class="footer-nav__link">スキルセット</a>
        </li>
        <li class="footer-nav__item">
          <a href="#contact" class="footer-nav__link">仕事の相談</a>
        </li>
      </ul>
      <p class="footer__copyright">
        &copy; 2019.
      </p>
    </footer>
  </div>
</template>

<style lang="scss" scoped>
.header {
  padding: 0 16px;
  display: flex;
  justify-content: space-between;
  line-height: 56px;
  color: #fff;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  box-sizing: border-box;
  background: rgba(0, 0, 0, .8);
  box-shadow: 0 0 10px rgba(0, 0, 0, .5);
  @include sp {
    font-size: 24px;
  }
}
</style>
