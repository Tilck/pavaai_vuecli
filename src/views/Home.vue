<template>
  <div class="home">
    <MainMenu />
    <HomeSection />
    <BestQualities />
  </div>
</template>

<script>
// @ is an alias to /src
import MainMenu from "@/components/MainMenu.vue";
import HomeSection from "@/components/HomeSection.vue";
import BestQualities from "@/components/BestQualities.vue";

export default {
  name: "home",
  components: {
    MainMenu,
    HomeSection,
    BestQualities
  }
};
</script>

<style lang="scss">

a,
a:hover,
a:active,
a:focus {
  text-decoration: none;
  outline: none;
}
a,
button,
a span {
  -webkit-transition: 0.2s ease-in-out;
  transition: 0.2s ease-in-out;
}

.btn:focus,
.btn:active {
  outline: inherit;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  /*    direction: rtl;*/
}
p {
  margin: 0 0 15px;
}

.clear {
  clear: both;
}

img {
  max-width: 100%;
}
textarea,
input[type="text"],
input[type="password"],
input[type="datetime"],
input[type="datetime-local"],
input[type="date"],
input[type="month"],
input[type="time"],
input[type="week"],
input[type="number"],
input[type="email"],
input[type="url"],
input[type="search"],
input[type="tel"],
input[type="color"],
.uneditable-input {
  outline: none;
  border-color: #ccc;
}

.form-control {
  border-radius: 0px;
  border: 1px solid #ccc;
  box-shadow: inset 0 0px 0px rgba(0, 0, 0, 0);
}

.form-control:focus {
  border-color: #bcefeb;
  outline: 0;
  box-shadow: inset 0 0px 0px rgba(0, 0, 0, 0.075),
    0 0 0px rgba(102, 175, 233, 0.6);
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 300;
  margin: 0;
  /*font-family: 'montserratbold';*/
}

h1 {
  font-size: 2.75rem;
  line-height: 4rem;
  color: #fff;
  font-weight: 700;
  font-family: "Montserrat", sans-serif;
  text-transform: uppercase;
}
h2 {
  font-size: 2.313rem;
  line-height: 3rem;
  text-transform: uppercase;
  font-weight: 400;
  font-family: "Montserrat", sans-serif;
}
h3 {
  font-size: 1.375rem;
  font-family: "Lato", sans-serif;
}
h4 {
  font-size: 1.625rem;
  line-height: 2rem;
  margin-bottom: 1rem;
  font-weight: 400;
  font-family: "Montserrat", sans-serif;
}
h5 {
  font-size: 1.125rem;
  margin-bottom: 1rem;
  text-transform: uppercase;
  font-weight: 600;
}
h6 {
  font-size: 1rem;
  margin-bottom: 0.9rem;
  font-weight: 700;
  text-transform: uppercase;
  font-family: "Lato", sans-serif;
}

h1 span {
  color: #fab704;
}
h2 span {
  color: #fab704;
}
h3 span {
  color: #fab704;
}
p span {
  color: #fab704;
}
p {
  line-height: 1.5rem;
}
p:last-child {
  margin-bottom: 0px;
}
/*.home-wrap h1,*/
.home-wrap h2,
.home-wrap h3,
.home-wrap h4,
.home-wrap h5,
.home-wrap p {
  color: #ffffff;
}

.blackbg {
  background: #262626;
}
.whitebg {
  background: #ffffff;
}
.textwhite {
  color: #fff;
}
.textblack {
  color: #262626;
}

.lightbg {
  background-color: #f9f9f9;
}
.transition {
  -webkit-transition: all 300ms linear;
  transition: all 300ms linear;
}

.outofsectiontext {
  margin-top: 40px;
}

/*
Section
*/
.sections {
  padding-top: 60px;
  padding-bottom: 105px;
  /*overflow: hidden;*/
}

.sections.footer {
  padding-bottom: 80px;
}

section .subtitle h5 {
  margin-top: 10px;
  font-size: 1.3rem;
}

.parallax-section {
  max-width: 100%;
  color: #ffffff;
}

section .title-half h2 {
  font-size: 3rem;
  line-height: 4rem;
  font-weight: 300;
  margin-bottom: 1.4rem;
}

section .subtitle-half h5 {
  font-weight: 100;
  font-size: 17px;
}

ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

.overlay {
  background-color: rgba(41, 39, 34, 0.55);
  width: 100%;
  height: 1000px;
}

.home-overlay {
  background-color: rgba(41, 39, 34, 0.75);
  width: 100%;
  height: 100%;
  position: absolute;
  left: 0;
  top: 0;
}

.video_overlay {
  background-color: rgba(41, 39, 34, 0.95);
  width: 100%;
  height: 100%;
  position: absolute;
  left: 0;
  top: 0;
}

.no-padding {
  padding: 0 !important;
  margin: 0 !important;
}

.fluid-blocks-col {
  padding: 70px 40px 0 80px;
}

.fluid-blocks-col-right {
  padding: 70px 80px 0 40px;
}

/*
Separator
*/
.clogo_borderBottom {
  width: 100%;
  height: 20px;
  background: #1cbba0;
  overflow: hidden;
}

.blackdividerauto {
  height: 1px;
  width: 125px;
  margin: 0px auto;
  position: relative;
  background: #000;
}

.blackdividerauto:after {
  height: 3px;
  width: 45px;
  margin: -1px auto;
  position: absolute;
  background: #ca1f26;
  content: "";
  left: 32%;
}

.whitedividerauto {
  height: 1px;
  width: 50px;
  margin: 10px auto;
  position: relative;
  background: #fff;
}

.separator {
  height: 3px;
  width: 100px;
  margin: 10px auto;
  position: relative;
  background: #ffba00;
}

.separator:after {
  height: 3px;
  width: 50px;
  margin: 0px auto;
  position: absolute;
  background: #898989;
  right: 0;
  top: 0;
  content: "";
}

.separatorhome3 {
  background-color: #0278ba;
  background-image: -webkit-linear-gradient(
    45deg,
    rgba(255, 255, 255, 0.35) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.35) 50%,
    rgba(255, 255, 255, 0.35) 75%,
    transparent 75%,
    transparent
  );
  background-image: linear-gradient(
    45deg,
    rgba(255, 255, 255, 0.35) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.35) 50%,
    rgba(255, 255, 255, 0.35) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  height: 5px;
  width: 70px;
  margin: 15px 0;
}

.separatorhome3auto {
  background-color: #0278ba;
  background-image: -webkit-linear-gradient(
    45deg,
    rgba(255, 255, 255, 0.35) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.35) 50%,
    rgba(255, 255, 255, 0.35) 75%,
    transparent 75%,
    transparent
  );
  background-image: linear-gradient(
    45deg,
    rgba(255, 255, 255, 0.35) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.35) 50%,
    rgba(255, 255, 255, 0.35) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  height: 5px;
  width: 70px;
  margin: 15px auto;
}

/*
Button
*/

.btn {
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  text-transform: uppercase;
}

.btn:hover {
  background: #fab704;
  color: #fff;
}

.btn-default {
  border: 1px solid #fff;
  background: transparent;
  color: #fff;
  padding: 0.7rem 2rem;
  border-radius: 0;
}

.btn-default-black {
  border: 1px solid #444;
  background: transparent;
  color: #444;
}

.btn-md {
  background: #fab704;
  padding: 0.7rem 2rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  width: 160px;
}

.btn-lg {
  background: #3c414c;
  padding: 0.7rem 3rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.btn-lg2 {
  background: #fab704 !important;
  padding: 0.7rem 3rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

.btn-raund {
  border-radius: 5px !important;
}

/*
h2 Button
*/

.h22.btn {
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  text-transform: uppercase;
}

.h22.btn:hover {
  background: #ca1f26;
  color: #fff;
}

.h22.btn-default {
  border: 1px solid #fff;
  background: transparent;
  color: #fff;
  padding: 0.7rem 2rem;
  border-radius: 0;
}

.h22.btn-default-black {
  border: 1px solid #444;
  background: transparent;
  color: #444;
}

.h22.btn-md {
  background: #ca1f26;
  padding: 0.7rem 2rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  width: 160px;
}

.h22.btn-lg {
  background: #3c414c;
  padding: 0.7rem 3rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

/*
h3 Button
*/

.h33.btn {
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  text-transform: uppercase;
}

.h33.btn:hover {
  background: #0278ba;
  color: #fff;
}

.h33.btn-default {
  border: 1px solid #fff;
  background: transparent;
  color: #fff;
  padding: 0.7rem 2rem;
  border-radius: 0;
}

.h33.btn-default-black {
  border: 1px solid #444;
  background: transparent;
  color: #444;
}

.h33.btn-md {
  background: #0278ba;
  padding: 0.7rem 2rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
  width: 160px;
}

.h33.btn-lg {
  background: #3c414c;
  padding: 0.7rem 3rem;
  border: 0px solid #fff;
  color: #fff;
  border-radius: 0;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

/*socail icon*/
a i.share {
  color: #949494;
  margin-right: 10px;
  -webkit-transition: all 0.6s;
  transition: all 0.6s;
}
a i.share:hover {
  color: #fa5454;
}

.post_text_color {
  color: #949494;
}

/*
Extra height css
*/
.m-r-15 {
  margin-right: 15px;
}
.m-l-15 {
  margin-left: 15px;
}
.margin-top-10 {
  margin-top: 10px;
}
.margin-top-20 {
  margin-top: 20px;
}
.margin-bottom-20 {
  margin-bottom: 20px;
}
.margin-top-30 {
  margin-top: 30px;
}
.margin-bottom-30 {
  margin-bottom: 30px;
}
.margin-top-40 {
  margin-top: 40px;
}
.margin-top-50 {
  margin-top: 50px;
}
.margin-bottom-40 {
  margin-bottom: 40px;
}
.margin-top-60 {
  margin-top: 60px;
}
.margin-80 {
  margin-top: 80px;
  margin-bottom: 80px;
}
.margin-bottom-60 {
  margin-bottom: 60px;
}
.margin-top-80 {
  margin-top: 80px;
}
.margin-bottom-80 {
  margin-bottom: 80px;
}
.m_t__b {
  margin: 14rem 0;
}
.p_t__b {
  padding: 6rem 0;
}
.padding-top-20 {
  padding-top: 1.33rem;
}
.padding-bottom-20 {
  padding-bottom: 1.33rem;
}
.padding-top-30 {
  padding-top: 1.875rem;
}
.padding-bottom-30 {
  padding-bottom: 1.875rem;
}
.padding-top-40 {
  padding-top: 2.66rem;
}
.padding-bottom-40 {
  padding-bottom: 2.66rem;
}
.padding-top-60 {
  padding-top: 5rem;
}
.padding-bottom-60 {
  padding-bottom: 5rem;
}
.padding-top-80 {
  padding-top: 5.714rem;
}
.padding-bottom-80 {
  padding-bottom: 5.714rem;
}
.padding-top-90 {
  padding-top: 6.429rem;
}
.padding-bottom-90 {
  padding-bottom: 6.429rem;
}
.padding-bottom-0 {
  padding-bottom: 0;
}
.p_l_r {
  padding-left: 5.714rem;
  padding-right: 5.714rem;
}
/*padding*/
.padding-twenty {
  padding: 10px 0;
}
.padding-fourty {
  padding: 20px 0;
}
.padding-sixty {
  padding: 30px 0;
}
.padding-eighty {
  padding: 40px 0;
}
/*border*/
.no-border-top {
  border-top: 0px solid transparent !important;
}
.no-border-rigth {
  border-right: 0px solid transparent !important;
}

/*for placeholder changes*/

input::-webkit-input-placeholder {
  color: #ddd;
  font-style: italic;
}
input::-moz-placeholder {
  color: #ddd;
  font-style: italic;
}
input::-ms-input-placeholder {
  color: #ddd;
  font-style: italic;
}
textarea::-webkit-input-placeholder {
  color: #ddd;
  font-style: italic;
  padding: 5px;
}
textarea::-moz-input-placeholder {
  color: #ddd;
  font-style: italic;
  padding: 5px;
}
textarea::-ms-input-placeholder {
  color: #ddd;
  font-style: italic;
  padding: 5px;
}
.culmn {
  width: 100%;
  overflow: hidden;
}

/*heading title all area*/

.head_title {
  width: 60%;
  margin: 0 auto;
  margin-bottom: 4rem;
}
.head_title h2 {
  font-family: "Montserrat", sans-serif;
  font-weight: 400;
  margin-bottom: 1rem;
}
.head_title p {
  font-weight: 300;
}
</style>
