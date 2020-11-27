<template>
  <div class="container">
    <div class="fv-about-us">
      <div class="fv-head">
        <div class="fv-logo">
          <nuxt-link to="/">
             <img src="~/assets/img/site-logo.png" alt="site-logo" />
          </nuxt-link>
        </div>
        <HamburgerMenuSection />
      </div>
      <div class="main-copy about-us">
        <h1>ABOUT US</h1>
        <p class="main-copy-txt1">DIGSMILE について</p>
      </div>
    </div>

    <div class="vison">
      <div class="vision-txt">
        <h2 class="ttl">VISION</h2>
        <h3>デザインで人を笑顔にする会社</h3>
        <p>
          私達のデザインで人が笑顔になる。<br />
          <br />
          そんなデザインを目指しています。<br />
          <br />
          私達が考える人を笑顔にできるデザインとは、<br />
          デザインが課題を適切に解決ができているかどうか。<br />
          <br />
          ビジュアルだけではなく、<br />
          本当に求められているものは何かを考え抜いて、<br />
          デザインしていきたい。<br />
          <br />
          誰かの幸せを創ることも、<br />
          世界の常識を変えていくことだってできる。<br />
          <br />
          私達はデザインの力を信じています。
        </p>
      </div>
    </div>

    <div class="ceo">
      <div class="ceo-img">
        <img src="~/assets/img/ceo-img.png" alt="" />
      </div>
      <div class="ceo-txt">
        <h2 class="ttl">CEO MESSAGE</h2>
        <p>
          良いデザインは人を幸せにする。<br />
          <br />
          私達はそう信じています。<br />
          <br />
          デザインを通して、ビジネスの課題とユーザーの課題を解決することで、世の中を幸せにしていきたい。<br />
          <br />
          現在はあらゆるプロダクトがデジタル化されており、デザイナーに対する需要はますます高まっています。それとともに、期待される役割も幅広くなりつつあります。<br />
          <br />
          クリエイティブで社会の可能性を切り開いていく。<br />
          <br />
          変化の激しい現代、私達はデザインの力で社会を良い方向に変革していく企業を目指していきます。
        </p>
      </div>
    </div>
    <div class="conpany">
      <h2 class="ttl">COMPANY</h2>
      <table>
        <tr>
          <td class="table-left">社名</td>
          <td>株式会社DIGSMILE</td>
        </tr>
        <tr>
          <td class="table-left">代表取締役</td>
          <td>テイラー・スウィフト</td>
        </tr>
        <tr>
          <td class="table-left">設立</td>
          <td>2020年1月1日</td>
        </tr>
        <tr>
          <td class="table-left">資本金</td>
          <td>1億円</td>
        </tr>
        <tr>
          <td class="table-left">所在地</td>
          <td>東京都新宿区☓☓0-0-0</td>
        </tr>
        <tr>
          <td class="table-left">電話番号</td>
          <td>03-0000-00000</td>
        </tr>
      </table>
    </div>
    <div class="map">
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7707.241214319456!2d139.696656938902!3d35.68941615332635!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x60188cd0d6b1ba1f%3A0x1c32a1f1ecacfdd5!2z5paw5a6_6aeF!5e0!3m2!1sja!2sjp!4v1596448367351!5m2!1sja!2sjp"
        width="1100"
        height="360"
        frameborder="0"
        style="border: 0;"
        allowfullscreen=""
        aria-hidden="false"
        tabindex="0"
      ></iframe>
    </div>
    <FooterSection />
  </div>
</template>

<script>
import FooterSection from "~/components/Footer.vue";
import HamburgerMenuSection from '~/components/Hamburger_menu.vue';

export default {
  components:{
    FooterSection,
    HamburgerMenuSection,
  }
}
</script>

<style>

</style>
