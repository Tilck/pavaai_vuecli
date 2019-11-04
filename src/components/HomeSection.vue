<template>
  <section id="home" class="home home1banner">
    <!--<div class="home-overlay"></div>-->
    <div class="container-fluid">
      <div class="row">
        <div
          id="xsslider"
          class="carousel home1_slider xs_slide_spread xsswipe slide_xs_ease kenburns_zoomInOut xs_indicators_line xs_control_square"
          data-ride="carousel"
          data-pause="hover"
          data-interval="false"
          data-duration="1000"
        >
          <!-- Wrapper For Slides -->
          <div class="carousel-inner" role="listbox">
            <div class="item active">
              <img src="assets/images/home1bg.jpg" alt="home1bg" />
              <div class="overlay"></div>
              <!-- Slide Text Layer -->
              <div class="slide_style_3 slide_style_left">
                <div class="home_slider_text textwhite">
                  <h1 data-animation="animated zoomInRight">
                    Доставка грузов из
                    <br />
                    <span>Турции, ОАЭ, Европы</span>
                  </h1>
                  <h2 data-animation="animated zoomInRight">и других стран</h2>
                  <a
                    href="#"
                    class="btn btn-default m-r-15 margin-top-20"
                    data-animation="animated zoomInRight"
                  >Подробнее</a>
                </div>
              </div>
            </div>

            <div class="item">
              <img src="assets/images/home2bg.jpg" alt="home2bg" />
              <div class="overlay"></div>
              <!-- Slide Text Layer -->
              <div class="slide_style_3 slide_style_center">
                <div class="home_slider_text textwhite">
                  <h1 data-animation="animated zoomInRight">
                    Ваш надежный
                    <span>логистический партнер</span>
                  </h1>
                  <p data-animation="animated zoomInRight">
                    Международные грузоперевозки – лучший сервис по доставке в
                    любую точку Европы. Наиболее распространенный контракт на международные перевозки – это доставка
                    от склада к складу с оформлением сопутствующих таможенных документов, страхованием объекта и
                    ответственности перевозчика и экспедитора.
                  </p>
                  <a
                    href="#"
                    class="btn btn-default m-r-15 margin-top-20"
                    data-animation="animated zoomInRight"
                  >Рассчитать стоимость</a>
                </div>
              </div>
            </div>
          </div>
          <!-- <h1 style="text-align: center;" -->
          <!-- Left Control -->
          <a class="left carousel-control" href="#xsslider" role="button" data-slide="prev">
            <span class="fa fa-angle-left" aria-hidden="true"></span>
            <!--                                    <span>prev</span>-->
            <!--<span class="sr-only">Previous</span>-->
          </a>

          <!-- Right Control -->
          <a class="right carousel-control" href="#xsslider" role="button" data-slide="next">
            <span class="fa fa-angle-right" aria-hidden="true"></span>
            <!--                                    <span>next</span>-->
            <!--<span class="sr-only">Next</span>-->
          </a>
        </div>
        <!-- End Bootstrap xsslider Slider -->
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.home1 .main_home{
    outline: none;
    overflow:hidden;
}
/*slider home*/
.home1_slider .carousel-inner .item img{
    height: 750px;
}

.home1_slider .home_slider_text{
    width:80%;
    margin:0px auto;
    padding-bottom: 10rem;
}

.home1_slider .carousel-control.left{
    width:40px;
    height: 40px;
    line-height: 40px;
    color:#fff;
    background: #3c414c;
    position: absolute;
    z-index: 999;
    top: 85%;
    font-size:1.5rem;
    -webkit-transition: all 0.6s;
    transition: all 0.6s;
    left:10%;
    text-align: center;
    border-radius:0;
}
.home1_slider .carousel-control.right{
    width: 40px;
    height: 40px;
    line-height: 40px;
    color: #fff;
    background: #3c414c;
    position: absolute;
    z-index: 999;
    top: 85%;
    font-size:1.5rem;
    -webkit-transition: all 0.6s;
    transition: all 0.6s;
    left:14%;
    text-align: center;
    border-radius:0;
}
.home1_slider .carousel-control.left:hover{
    color:#fff;
    background: #fab704;
}
.home1_slider .carousel-control.right:hover{
    color: #fff;
    background: #fab704;
}
</style>