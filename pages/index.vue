<template>
  <div>
    <div class="hero">
      <div class="container">
        <p class="hero__message">
          はじめてのWebサイト
        </p>
        <a href="#contact" class="button">お問い合わせ</a>
      </div>
    </div>
    <div id="profile" class="section">
      <div class="container">
        <h2 class="heading">
          <span class="heading__main">PROFILE</span>
          <span class="heading__sub">プロフィール</span>
        </h2>
        <div class="profile">
          <figure class="profile__photo" />
          <div class="profile__body">
            <p class="profile__name">
              <ruby>
                Muroya<rt>ムロヤ</rt><rt>-Nozomi</rt>
              </ruby>
            </p>
            <p class="profile__text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, rerum pariatur. Pariatur labore porro dolor sit placeat? Iure necessitatibus dolor earum quia sed cumque, excepturi ducimus eius libero aliquam sequi!
            </p>
            <div class="profile__sns">
              <a href="https://twitter.com/TwitterDev?ref_src=twsrc%5Etfw%7Ctwcamp%5Eembeddedtimeline%7Ctwterm%5Eprofile%3ATwitterDev&ref_url=http%3A%2F%2Flocalhost%3A3000%2F" target="_blank" rel="noopener" class="sns-icon">
                <i class="fab fa-twitter" />
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="twitter">
      <a class="twitter-timeline" data-chrome="nofooter noheader noborders" data-height="400" href="https://twitter.com/TwitterDev/timelines/539487832448843776?ref_src=twsrc%5Etfw">National Park Tweets - Curated tweets by TwitterDev</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8" />
    </div>
    <div id="skill" class="section section--light">
      <div class="container">
        <h2 class="heading">
          <span class="heading__main">SKILL</span>
          <span class="heading__sub">スキル</span>
        </h2>
        <div class="grid">
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fab fa-html5" />
              </figure>
              <h3 class="skill__title">
                HTML/CSS
              </h3>
              <p class="skill__description">
                HTML/CSSを正しく設計することができます。
              </p>
            </div>
          </div>
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fab fa-adobe" />
              </figure>
              <h3 class="skill__title">
                AdobeXD
              </h3>
              <p class="skill__description">
                デザインツールを扱うことができます。
              </p>
            </div>
          </div>
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fab fa-github" />
              </figure>
              <h3 class="skill__title">
                Git開発
              </h3>
              <p class="skill__description">
                GitHubでソースレビューを通した開発ができます。
              </p>
            </div>
          </div>
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fab fa-wordpress-simple" />
              </figure>
              <h3 class="skill__title">
                WordPress
              </h3>
              <p class="skill__description">
                WordPressによるメディア設計が可能です。
              </p>
            </div>
          </div>
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fab fa-js-square" />
              </figure>
              <h3 class="skill__title">
                jQuery
              </h3>
              <p class="skill__description">
                jQueryによるUI実装が可能です。
              </p>
            </div>
          </div>
          <div class="card">
            <div class="skill">
              <figure class="skill__icon">
                <i class="fas fa-chart-line" />
              </figure>
              <h3 class="skill__title">
                SEO
              </h3>
              <p class="skill__description">
                SEOに適したマークアップと運営構築が可能です。
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="section section--dark">
      <div class="container">
        <div class="card">
          <div class="movie">
            <div>
              <iframe
                class="movie__iframe"
                width="560"
                height="315"
                src="https://www.youtube.com/embed/Fs1fabWUmDM?showinfo=0&rel=0&controls=0&modestbranding=1"
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              />
            </div>
            <div class="movie__body">
              <h2 class="movie__title">
                News
              </h2>
              <p class="movie__date">
                2019.11.1
              </p>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis totam eius tempora fuga ad facilis repudiandae modi, numquam doloribus, mollitia sed minima accusantium nulla non eveniet. At voluptate aspernatur voluptates?</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3241.673665996426!2d139.72707631525822!3d35.6604109801992!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188b770913970d%3A0xccc3467fcb15b353!2z44Kw44O844Kw44Or5ZCI5ZCM5Lya56S-!5e0!3m2!1sja!2sjp!4v1557743115208!5m2!1sja!2sjp" width="600" height="450" style="border:0" allowfullscreen />
    <div id="contact" class="section">
      <h2 class="heading">
        <span class="heading__main">CONTACT</span>
        <span class="heading__sub">お問い合わせ</span>
      </h2>
      <form class="contact">
        <label for="name" class="contact__label">名前<span class="required">*</span></label>
        <input
          id="name"
          type="text"
          name="name"
          class="input"
          autocomplete="name"
          required
        >
        <label for="email" class="contact__label">メールアドレス<span class="required">*</span></label>
        <input id="email" type="email" name="email" class="input" required>
        <label for="body" class="contact__label">内容<span class="required">*</span></label>
        <textarea id="body" name="body" class="input input--textarea" required />
        <span />
        <div class="contact__footer">
          <button type="submit" class="button button--sm button--black">
            送信
          </button>
        </div>
      </form>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  background: center/cover url(/imges/hero.jpg);
  padding: 280px 0;
  color: #fff;
  &__message {
  font-size: 40px;
  font-weight: bold;
  line-height: 1.8;
  margin-bottom: 32px;
  }
}
</style>
