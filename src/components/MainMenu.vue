<template>
  <div>
    <div class="preloader">
      <div class="loaded atebits-loader">&nbsp;</div>
    </div>
    <nav class="navbar home1_menu navbar-default navbar-fixed navbar-mobile bootsnav">
      <div class="container">
        <div class="row">
          <div class="head_top_social_area">
            <div class="head_top_social">
              <div class="col-sm-7">
                <ul class="list-inline pull-right">
                  <li>
                    <a style="color: white" href>
                      Компания «Matiiets» Ваш надежный перевозчик
                      <i class="fa fa-long-arrow-right"></i>
                    </a>
                  </li>
                </ul>
              </div>

              <div class="col-sm-5">
                <div class="top_socail_icon_area pull-right">
                  <ul class="list-inline">
                    <li>
                      <a href>
                        <i class="fa fa-facebook"></i>
                      </a>
                    </li>
                    <li>
                      <a href>
                        <i class="fa fa-twitter"></i>
                      </a>
                    </li>
                    <li>
                      <a href>
                        <i class="fa fa-google-plus"></i>
                      </a>
                    </li>
                    <li>
                      <a href>
                        <i class="fa fa-linkedin"></i>
                      </a>
                    </li>
                    <li>
                      <a href>
                        <i class="fa fa-dribbble"></i>
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="nav-top clearfix">
            <div class="logo"></div>
            <div class="call_us_area">
              <ul class="list-inline pull-right text-left">
                <li>
                  <span class="icon icon-Phone2"></span>
                  <span>
                    Звоните прямо сейчас
                    <br />
                    <a href="tel:+380674330990">+38 (067) 433-09-90</a>
                  </span>
                </li>
                <li>
                  <span class="icon icon-Mail"></span>
                  <span>
                    Остались вопросы?
                    <br />
                    <a href="mailto:Matiiets@gmail.com">Matiiets@gmail.com</a>
                  </span>
                </li>
                <li>
                  <span class="icon icon-Pointer"></span>
                  <span>
                    Наш адрес:
                    <br />
                    <a
                      href="https://goo.gl/maps/HJxfMLJ1wQgtfi1r8"
                    >г. Винница, улица 600 Риччя, 20\2</a>
                  </span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>

      <div class="container">
        <!-- Start Top Search -->
        <div class="top-search">
          <div class="container">
            <div class="input-group">
              <span class="input-group-addon">
                <i class="fa fa-search"></i>
              </span>
              <input type="text" class="form-control" placeholder="Search" />
              <span class="input-group-addon close-search">
                <i class="fa fa-times"></i>
              </span>
            </div>
          </div>
        </div>
        <!-- End Top Search -->

        <!-- Start Header Navigation -->
        <div class="navbar-header">
          <button
            type="button"
            class="navbar-toggle"
            data-toggle="collapse"
            data-target="#navbar-menu"
          >
            <i class="fa fa-bars"></i>
          </button>
          <a class="navbar-brand" href="#brand">
            <img src="assets/images/h1logo.png" class="logo" alt />
          </a>
        </div>
        <!-- End Header Navigation -->

        <!-- Collect the nav links, forms, and other content for toggling -->
        <div class="collapse navbar-collapse" id="navbar-menu">
          <div class="main-nav-border"></div>
          <ul
            class="nav navbar-nav navbar-left text-uppercase"
            data-in="fadeInDown"
            data-out="fadeOutUp"
          >
            <li>
              <a href="#home">Главная</a>
            </li>
            <li>
              <a href="#featured">О нас</a>
            </li>
            <li>
              <a href="#extrafeatures">Вопрос-ответ</a>
            </li>
            <li>
              <a href="#team">Услуги</a>
            </li>
            <li>
              <a href="#testimonial">Отзывы</a>
            </li>
            <li>
              <a href="#request">Расчитать стоимость доставки</a>
            </li>
            <li>
              <a href="#footer_weidget">Контакты</a>
            </li>
          </ul>
          <!-- /.language-start -->
          <div class="dropdown" style="float:right;">
            <span style="color:white" class="fa fa-dribbble"></span>
            <button class="dropbtn">Русский</button>
            <div class="dropdown-content">
              <a href="#">Английский</a>
              <a href="#">Украинский</a>
            </div>
          </div>
        </div>
        <!-- language-end -->

        <!-- <div class="attr-nav">
          <select class="localization" name="localization" id="localization">
            <option>Русский</option>
            <option>English</option>
            <option>Українська</option>
          </select>
        </div>-->
      </div>
    </nav>
  </div>
</template>

<style scoped lang="scss">
.preloader {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: #fefefe;
  z-index: 99999;
  height: 100%;
  width: 100%;
  overflow: hidden !important;
}

.loaded {
  width: 60px;
  height: 60px;
  position: absolute;
  left: 50%;
  top: 50%;
  margin: -20px 0 0 -20px;
}
.atebits-loader:not(:required) {
  background: rgba(0, 0, 0, 0.5);
  display: inline-block;
  width: 9px;
  height: 9px;
  overflow: hidden;
  text-indent: -9999px;
  -moz-box-shadow: rgba(0, 0, 0, 0.5) -12px -12px 0 0, rgba(0, 0, 0, 0.5) 12px -12px 0 0, rgba(0, 0, 0, 0.5) -12px 0 0 0, rgba(0, 0, 0, 0.5) 12px 0 0 0, rgba(0, 0, 0, 0.5) -12px 12px 0 0, rgba(0, 0, 0, 0.5) 0 12px 0 0, rgba(0, 0, 0, 0.5) 12px 12px 0 0;
  -webkit-box-shadow: rgba(0, 0, 0, 0.5) -12px -12px 0 0, rgba(0, 0, 0, 0.5) 12px -12px 0 0, rgba(0, 0, 0, 0.5) -12px 0 0 0, rgba(0, 0, 0, 0.5) 12px 0 0 0, rgba(0, 0, 0, 0.5) -12px 12px 0 0, rgba(0, 0, 0, 0.5) 0 12px 0 0, rgba(0, 0, 0, 0.5) 12px 12px 0 0;
  box-shadow: rgba(0, 0, 0, 0.5) -12px -12px 0 0, rgba(0, 0, 0, 0.5) 12px -12px 0 0, rgba(0, 0, 0, 0.5) -12px 0 0 0, rgba(0, 0, 0, 0.5) 12px 0 0 0, rgba(0, 0, 0, 0.5) -12px 12px 0 0, rgba(0, 0, 0, 0.5) 0 12px 0 0, rgba(0, 0, 0, 0.5) 12px 12px 0 0;
  -moz-animation: atebits-loader 8s infinite ease-in-out;
  -webkit-animation: atebits-loader 8s infinite ease-in-out;
  animation: atebits-loader 8s infinite ease-in-out;
  -moz-transform-origin: 50% 50%;
  -ms-transform-origin: 50% 50%;
  -webkit-transform-origin: 50% 50%;
  transform-origin: 50% 50%;
}
.dropbtn {
  background-color: #017cc0;
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
  z-index: 1;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  right: 0;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {
  background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown:hover .dropbtn {
  background-color: #018cd9;
}
/*Start home Menu One*/
.home1_menu .head_top_social_area:before {
  left: 96.3%;
  top: 0;
  border: solid transparent;
  content: " ";
  height: 0;
  width: 0;
  position: absolute;
  pointer-events: none;
  border-color: rgba(60, 65, 76, 0);
  border-right-color: #fff;
  border-width: 44px 44px 0 0;
}
.home1_menu .head_top_social_area {
  /*    -webkit-transform: skewX(-45deg);
        -moz-transform: skewX(-45deg);
        transform: skewX(-45deg);*/
  background: #3c414c;
  overflow: hidden;
  /*    -webkit-clip-path: polygon(100% 0, 100% 65%, 100% 100%, 0 100%, 10% 0%);
        -moz-clip-path: polygon(100% 0, 100% 65%, 100% 100%, 0 100%, 10% 0%);
        clip-path: polygon(100% 0, 100% 65%, 100% 100%, 0 100%, 10% 0%);*/
  /*clip-path: inset(100px 50px 0px 0px);*/
  /*border-bottom-right-radius: 6px 2px;*/
}
.home1_menu .head_top_social_area:after {
  -webkit-transform: skewX(47deg);
  -moz-transform: skewX(47deg);
  transform: skewX(47deg);
  background: #fff;
  width: 25.5%;
  padding: 1.4rem;
  position: absolute;
  left: -44px;
  top: 0;
  content: "";
  border-right: 1px solid #ddd;
}
nav.small.home1_menu .head_top_social_area:after {
  top: -45px;
}
// .home1_menu .head_top_social {
//   /*    -webkit-transform: skewX(45deg);
//         -moz-transform: skewX(45deg);
//         transform: skewX(45deg);*/
// }

.home1_menu .head_top_social ul li a {
  padding: 0.6rem 0.2rem;
  display: inline-block;
}

.home1_menu .head_top_social ul li a {
  color: #b7b7b7;
}

.home1_menu .head_top_social ul li a i {
  color: #b7b7b7;
}
.home1_menu .head_top_social ul li a:hover {
  color: #fff;
}
.home1_menu .head_top_social ul li a:hover i {
  color: #fff;
}
.head_top_social .top_socail_icon_area ul li a i {
  color: #fff;
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
}
.home1_menu .head_top_social .top_socail_icon_area ul li a:hover i {
  color: #3c414c;
}
.home1_menu .head_top_social .top_socail_icon_area {
  background: #fab704;
  padding: 0rem 1.5rem;
  -webkit-transform: skewX(45deg);
  transform: skewX(45deg);
  margin-right: 10%;
}
.home1_menu .head_top_social .top_socail_icon_area ul.list-inline {
  -webkit-transform: skewX(-45deg);
  transform: skewX(-45deg);
}
/*End off top socail*/

/* navbar section */
.home2_menu.small {
  padding-top: 0px;
  padding-bottom: 0px;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 300;
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-color: rgba(0, 0, 0, 0.65) !important;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  height: 75px;
}
.home2_menu .attr-nav ul li.search a i {
  color: #fff;
}
.home2_menu .top-search .input-group-addon {
  color: #fff;
}

/*call us nav area*/
.home1_menu .navbar-brand {
  padding: 1px;
  /*width: 240px;*/
}

.home1_menu .call_us_area {
  padding: 1.5rem 0rem;
  overflow: hidden;
  position: relative;
}
.home1_menu .call_us_area:after {
  content: "";
  left: 17.45%;
  top: 0;
  position: absolute;
  background: #fff;
  -webkit-transform: skewX(51deg);
  transform: skewX(51deg);
  padding: 5.7rem;
  border-right: 1px solid #ddd;
  z-index: -1;
}
.home1_menu .call_us_area ul li {
  color: #1a1a1a;
  padding: 0.5rem 1rem;
}
.home1_menu .call_us_area ul li span.icon {
  display: inline-block;
  color: #1a1a1a;
  font-size: 2rem;
  padding: 0rem 0.5rem;
}
.home1_menu .call_us_area ul li span {
  display: inline-block;
  font-weight: 400;
}

/*main nav area*/

nav {
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
}
nav.navbar ul.nav > li > a:hover {
  background-color: transparent !important;
}
.home1_menu .head_top_social_area,
.nav-top {
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
}

small,
.small {
  font-size: 100% !important;
}

nav.navbar.home1_menu.bootsnav.navbar-fixed.small {
  height: 0px;
}
nav.small.home1_menu .head_top_social_area {
  margin-top: -44px;
}
nav.small.home1_menu .nav-top {
  margin-top: -114px;
}
.home1_menu.navbar > .container .navbar-brand {
  width: 275px;
  position: relative;
  top: -95px;
}
.home1_menu.navbar-default .navbar-collapse {
  border-color: #e7e7e7;
  background: #fab704;
  position: absolute;
  width: 100%;
  left: 0;
  top: 0;
}

.home1_menu .attr-nav {
//   float: right;
  display: inline-block;
  margin-left: 10px;
  margin-right: -15px;
  width: 350px;
  position: relative;
}

.home1_menu .attr-nav form {
  position: relative;
  background: #3c414c;
  width: 87%;
  float: right;
  margin: 0;
  padding: 5px 1px;
}
.home1_menu .attr-nav form input[type="text"] {
  background: transparent;
  padding: 1rem 5.5rem 1rem 4rem;
  width: 100%;
  border: 0;
  text-align: right;
  position: relative;
  z-index: 99;
}

.home1_menu .attr-nav form input[type="submit"] {
  position: absolute;
  right: 30px;
  top: 0;
//   background: url(../images/serch.png) no-repeat center right;
  text-indent: -99999px;
  border: 0;
  outline: 0;
  padding: 1.35rem;
  z-index: 99;
}

.home1_menu .attr-nav form:after {
  position: absolute;
  left: -12%;
  top: 0;
  background: #fab704;
  width: 0%;
  content: "";
  -webkit-transform: skewX(-35deg);
  transform: skewX(-35deg);
  padding: 1.989rem;
}

.home1_menu .collapse form input[type="text"] {
  position: relative;
  z-index: 99;
}

/* End off Home Menu One */
</style>
