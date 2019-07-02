<template>
  <div>
    <header class="header">
      <p class="header__logo">
        ポートフォリオ
      </p>
      <ul class="gnav">
        <li class="gnav__item">
          <nuxt-link to="/#profile" href="#profile" class="gnav__link">
            プロフィール
          </nuxt-link>
        </li>
      </ul>
      <ul class="gnav">
        <li class="gnav__item">
          <nuxt-link to="/#skill" class="gnav__link">
            スキルセット
          </nuxt-link>
        </li>
      </ul>
      <ul class="gnav">
        <li class="gnav__item">
          <nuxt-link to="/#contact" class="gnav__link">
            仕事の相談
          </nuxt-link>
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

<style lang="scss">
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

.gnav {
  display: flex;
  &__link {
    padding: 0 8px;
    font-size: 13px;
    position: relative;
    line-height: 56px;
    display: block;
    &:after {
      content: "";
      display: block;
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 4px;
      background: #fff;
      opacity: 0;
      transition: opacity .3s;
    }
    &:hover:after {
      opacity: 1;
    }
  }
  @include sp {
    display: none;
  }
}

.footer {
  padding: 16px;
  border-top: 1px solid rgba(0, 0, 0, .12);
  font-size: 12px;
  color: rgba(0, 0, 0, .6);
  display: flex;
  justify-content: space-between;
  @include sp {
    display: block;
  }
}

.footer-nav {
  display: flex;
  list-style: none;
  @include sp {
    display: block;
    line-height: 1.8;
    margin-bottom: 16px;
  }
  &__item + .footer-nav__item:before {
    content: "|";
    margin: 0 8px;
   @include sp {
     display: none;
    }
  }
  &__link {
  text-decoration: none;
  color: inherit;
  }
}

.section {
  padding: 80px 0;
  &--light {
    background: #fff;
  }
  &--dark {
    background: linear-gradient(to top right, #000, #2d033a);
  }
}
</style>
