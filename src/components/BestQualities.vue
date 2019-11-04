<template>
        <!-- Начало секции WE GIVE YOU THE BEST-->
    <section id="featured" class="featured">
      <div class="container">
        <div class="row">
          <div class="main_featured main_featured_home1">
            <div class="col-md-8">
              <div class="single_left_featured sections">
                <h2>Почему стоит работать <span>именно с нами?</span></h2>
                <p>
                  Компания <span style="color: #017cc0;"><b>“Мatiiets”</b></span>- это ведущий грузоперевозчик,
                  осуществляющий доставку грузов по Украине,
                  странам СНГ и Европы. За 25 лет работы компания завоевала высокую популярность в сфере
                  грузоперевозок, а так же заслужила высокий авторитет на рынке транспортных услуг.
                </p>


                <div class="f_service_area margin-top-60">
                  <div class="row">
                    <div class="col-sm-4">
                      <div class="f_single_service">
                        <div class="f_s_top_area">
                          <div class="f_s_top_left">
                            <div class="hexagon"><i class="fa fa-twitter"></i></div>

                          </div>
                          <div class="f_s_top_right text-right">
                            <span>01</span>
                          </div>
                        </div>
                        <div class="f_s_s_text margin-top-20">
                          <h6>Профессиональные сотрудники</h6>
                          <p>
                            Благодаря многолетнему опыту работы, наш штаб
                            сформирован исключительно из профессионалов,
                            качественно выполняющих свою работу.
                          </p>
                        </div>
                      </div>
                    </div>
                    <div class="col-sm-4">
                      <div class="f_single_service">
                        <div class="f_s_top_area">
                          <div class="f_s_top_left">
                            <div class="hexagon"><i class="fa fa-twitter"></i></div>
                          </div>
                          <div class="f_s_top_right text-right">
                            <span>02</span>
                          </div>
                        </div>

                        <div class="f_s_s_text margin-top-20">
                          <h6>Надежные автомобили и своя техническая база</h6>
                          <p>
                            Наш автопарк состоит исключительно из современных автомобилей.
                            Все машины своевременно проходят ТО и получают
                            соответствующую сертефикацию.
                          </p>
                        </div>

                      </div>
                    </div>
                    <div class="col-sm-4">
                      <div class="f_single_service">
                        <div class="f_s_top_area">
                          <div class="f_s_top_left">
                            <div class="hexagon"><i class="fa fa-twitter"></i></div>
                          </div>
                          <div class="f_s_top_right text-right">
                            <span>03</span>
                          </div>
                        </div>
                        <div class="f_s_s_text text-left margin-top-20">
                          <h6>Полная документация</h6>
                          <p>
                            Клиент всегда получает полную информацию по всем
                            видам документации: договорам, разрешениям,
                            таможенным документам, свидетельствам, сертификатам и т.д.
                          </p>
                        </div>

                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <div class="col-md-4">
              <div class="request_quot_area request_quot_area_home1">
                <div class="heading_request">
                  <div class="row">
                    <div class="col-xs-2">
                      <i class="fa fa-file-o"></i>
                    </div>
                    <div class="col-xs-10">
                      <h4>Остались вопросы?</h4>
                      <span>Мы с радостью на них ответим!</span>
                    </div>
                  </div>
                </div>
                <div class="quote-form">
                  <div class="col-12 col-sm-12">
                    <div id="quote-error"></div>
                  </div>
                  <!------------------------------------- Форма обратной связи------------------------- -->
                  <form method="post" action="assets/scripts/quote.php" class="contact-form col-12 col-sm-12"
                    id="quoteform">
                    <!-- Hidden Required Fields -->
                    <input type="hidden" name="project_name" value="Matiiets">
                    <input type="hidden" name="admin_email" value="tilck081195@gmail.com">
                    <input type="hidden" name="form_subject" value="Form Subject">
                    <!-- END Hidden Required Fields -->
                    <div class="row" style="margin: 0;">
                      <div class="col-12">
                        <div class="col-12 col-sm">
                          <div class="form-group">
                            <label for="name">Ваше имя <i>*</i></label>
                            <input type="text" name="form_name" class="form-control" id="name" placeholder="Введите имя"
                              required="">
                          </div>
                        </div>
                        <div class="col-12 col-sm">
                          <div class="form-group">
                            <label for="email">Введите ваш Email <i>*</i></label>
                            <input type="email" name="form_email" class="form-control" id="email"
                              placeholder="Введите email">
                          </div>
                        </div>
                        <div class="col-12 col-sm">
                          <div class="form-group">
                            <label for="tel">Введите ваш номер телефона <i>*</i></label>
                            <input type="tel" id="phone1" name="form_tel" class="form-control"
                              placeholder="Введите номер телефона" required="">
                          </div>
                        </div>
                        <div class="col-12 col-sm">
                          <div class="form-group">
                            <label for="text">Ваш вопрос</label>
                            <input type="text" name="form_text" class="form-control" id="text"
                              placeholder="Введите свой вопрос" required="">
                          </div>
                        </div>
                      </div>
                      <div class="col-sm-12 margin-top-20 text-center">
                        <input type="submit" id="submit" value="Заказать обратный звонок" class="btn btn-lg"
                          style="width: 100%; font-size: 14px;">
                      </div>
                    </div>
                  </form>
                  <!------------------------------------- Конец формы обратной связи------------------------- -->
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section><!-- Конец секции WE GIVE YOU THE BEST-->
</template>

<style lang="scss" scoped>
.main_featured_home1 .single_left_featured h2{
    margin-bottom:20px;
}
.main_featured_home1 .single_left_featured .f_s_top_area{
    width: 100%;
    margin: 0 auto;
    border-top: 1px solid #000;
    position: relative;
}
.main_featured_home1 .single_left_featured .f_s_s_text{
    overflow: hidden;
    width:100%;

}
.main_featured_home1 .f_s_top_left{
    width:20%;
    float: left;
}
.main_featured_home1 .f_s_top_right{
    width:40%;
    float: right;
    position: relative;
}
.main_featured_home1 .f_s_top_right span{
    width: 30px;
    height: 30px;
    background: #3c414c;
    text-align: center;
    border-radius: 50%;
    color: #fff;
    position: absolute;
    right: 0;
    top: -14px;
    line-height: 27px;
    font-size: 0.875rem;
}

.main_featured_home1 .single_left_featured .hexagon {
    position: relative;
    height: 50px;
    width: 50px;
    background: #3c414c;
    top: -25px;
}
.main_featured_home1 .single_left_featured .hexagon:before, .double:after {
    position: absolute;
    content: '';
}
.main_featured_home1 .single_left_featured .hexagon:before {
    top: 3px;  /* border width */
    left: 3px;  /* border width */
    height: calc(100% - 6px);  /* 100% - (2 * border width) */
    width: calc(100% - 6px);  /* 100% - (2 * border width) */
    background: #fff;
}
.main_featured_home1 .single_left_featured .hexagon, .hexagon:before, .double:after {
    -webkit-clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
    clip-path: polygon(50% 0%, 100% 25%, 100% 75%, 50% 100%, 0% 75%, 0% 25%);
}


.main_featured_home1 .single_left_featured .hexagon i{
    position: absolute;
    left: 25%;
    top: 25%;
    color:#3c414c;
    font-size:1.5rem;
}



/* form */
select:not([multiple]){
    -webkit-appearance:none;
    -moz-appearance:none;
    background-position:right 50%;
    background-repeat:no-repeat;
    background-image:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAMCAYAAABSgIzaAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyJpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuMC1jMDYwIDYxLjEzNDc3NywgMjAxMC8wMi8xMi0xNzozMjowMCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENTNSBNYWNpbnRvc2giIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6NDZFNDEwNjlGNzFEMTFFMkJEQ0VDRTM1N0RCMzMyMkIiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6NDZFNDEwNkFGNzFEMTFFMkJEQ0VDRTM1N0RCMzMyMkIiPiA8eG1wTU06RGVyaXZlZEZyb20gc3RSZWY6aW5zdGFuY2VJRD0ieG1wLmlpZDo0NkU0MTA2N0Y3MUQxMUUyQkRDRUNFMzU3REIzMzIyQiIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDo0NkU0MTA2OEY3MUQxMUUyQkRDRUNFMzU3REIzMzIyQiIvPiA8L3JkZjpEZXNjcmlwdGlvbj4gPC9yZGY6UkRGPiA8L3g6eG1wbWV0YT4gPD94cGFja2V0IGVuZD0iciI/PuGsgwQAAAA5SURBVHjaYvz//z8DOYCJgUxAf42MQIzTk0D/M+KzkRGPoQSdykiKJrBGpOhgJFYTWNEIiEeAAAMAzNENEOH+do8AAAAASUVORK5CYII=);
    padding: .5em;
    padding-right:1.5em;
}
input.form-control, select.form-control {
    height: 40px !important;
    font-size:14px;
}

.main_featured .request_quot_area.request_quot_area_home1{
    overflow: hidden;
    background: #f9f9f9;
    margin-top: -86px;
    box-shadow: 0px 2px 0px 0px #333;
}
.request_quot_area.request_quot_area_home1 .form-control{
    font-family: 'latolight_italic';
    height: 40px;
    border-radius: 0;
    color: #949494;
    font-style: italic;
}
.request_quot_area.request_quot_area_home1 textarea.form-control {
    height: 70px;
}
.request_quot_area.request_quot_area_home1 form{
    padding: 1.5rem 1rem 2.5rem 1rem;
}
.request_quot_area.request_quot_area_home1 .heading_request{
    background: #fab704;
    color:#fff;
    padding:1rem;
}
.request_quot_area.request_quot_area_home1 .heading_request i{
    font-size: 2rem;
    border-right: 1px solid #ddd;
    padding-right: 1rem;
    border-bottom: 1px solid #ddd;
    padding-bottom: 1rem;
}
.request_quot_area.request_quot_area_home1 .heading_request h4{
    margin-bottom: 0;
}
.request_quot_area.request_quot_area_home1 .heading_request span{
    font-size:1rem;
}
</style>