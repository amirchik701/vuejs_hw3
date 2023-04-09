<template>
  <header>
    <div class="img_header">
      <a href="/"
        ><img class="header_logo" src="./assets/img/header-logo.svg" alt=""
      /></a>
    </div>
  </header>

  <nav class="nav">
    <ul class="nav__list">
      <li class="nav__list_link"><a href="#">Жилые комплексы</a> </li>
      <li class="nav__list_link"><a href="#!">О компании</a> </li>
      <li class="nav__list_link"><a href="#!">Контакты</a> </li>
      <li class="nav__list_link"><a href="#!">Новости</a> </li>
      <li class="nav__list_link"><a href="#!">Акции</a> </li>
      <li class="nav__list_link"><a href="#!">Преимущества</a> </li>
    </ul>
    <!-- <li class="nav__list_link">Жилые комплексы</li>
      <li class="nav__list_link">О компании</li>
      <li class="nav__list_link">Контакты</li>
      <li class="nav__list_link">Новости</li>
      <li class="nav__list_link">Акции</li>
      <li class="nav__list_link">Преимущества</li> -->
  </nav>

  <main class="main">
    <div class="main__img">
      <img src="./assets/img/block1.png" alt="" />
    </div>

    <div class="main__block container">
      <div class="left">
        <div class="left__title">
          <h1 class="l__title">Почему лучше покупать в новостройках?</h1>
        </div>

        <div class="left__text">
          <p class="l__text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
            aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
            culpa qui officia deserunt mollit anim id est laborum. Sed ut
            perspiciatis unde omnis iste natus error sit voluptatem accusantium
            doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo
            inventore veritatis et quasi architecto beatae vitae dicta sunt
            explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur
            aut odit aut fugit, sed quia consequuntur magni dolores eos qui
            ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui
            dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed
            quia non numquam eius modi tempora incidunt ut labore et dolore
            magnam aliquam quaerat volupt atem.
          </p>
        </div>
      </div>

      <div class="right">
        <div class="r__contacts">
          <h2 class="r__title">Наши контакты</h2>
        </div>
        <div class="r__text">
          <p class="r_desc">
            Адрес: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
            do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
        <div class="r__number">
          <a class="r__num" href="tel:+998909009090">+99890 900 00 00 </a>
        </div>
        <div class="r__email">
          <a class="r__gmail" href="mailto:info@silverhouse.uz"
            >info@silverhouse.uz</a
          >
        </div>
      </div>
    </div>
  </main>

  <footer class="footer">
    <div class="container">
      <div class="footer__content">
        <div class="footer__left">
          <a href="/"><img src="./assets/img/footer-logo1.svg" alt="" /></a>
        </div>
        <div class="footer__right">
          <div class="fr__call">
            <h3 class="fr__text">Единый кол-центр (круглосуточно)</h3>
          </div>
          <div class="fr__num">
            <a class="fr__tel" href="tel:+998909000000">+99890 900 00 00</a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  text-decoration: none;
  list-style: none;
  box-sizing: border-box;
}

.container {
  max-width: 1140px;
  padding: 0 15px;
  margin: 0 auto;
}
.img_header {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}

.nav__list {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 30px;
  margin-top: 80px;
}

.nav__list_link a {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 21px;
  color: #8c8a8a;
}

.main__img {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}

.left {
  display: flex;
  flex-direction: column;
  gap: 25px;
  margin-top: 30px;
  background: #f0f0f0;
  padding: 50px 95px 50px 40px;
}

.l__title {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  line-height: 23px;

  color: #4581b7;
}

.l__text {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 27px;
  color: #808080;
  max-width: 595px;
}

.main__block {
  display: flex;
  gap: 30px;
}

.r__title {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 20px;
  line-height: 23px;

  color: #4581b7;
}

.r_desc {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 27px;
  max-width: 286px;
  /* or 169% */

  color: #808080;
}

.r__num {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 27px;
  color: #808080;
}

.r__gmail {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 27px;
  color: #808080;
}

.right {
  margin-top: 30px;
  display: flex;
  flex-direction: column;
  background: #f0f0f0;
  padding: 50px 24px 160px 40px;
  gap: 10px;
}

.r__text {
  padding-top: 25px;
}

.r__number {
  padding-top: 30px;
}

.r__email {
  padding-top: 50px;
}

.footer__content {
  display: flex;
  justify-content: space-between;
  width: 100%;
  background: #f0f0f0;
  margin-top: 30px;
  padding: 15px 40px;
}
.footer__l .fr__text {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 19px;
  color: #808080;
}

.fr__tel {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 25px;
  line-height: 29px;

  color: #808080;
}

.fr__text {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 19px;
  color: #808080;
}

.footer__right {
  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 10px;
}
</style>
