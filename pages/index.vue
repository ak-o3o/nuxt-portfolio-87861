<template>
  <div class="container">
    <div class="fv">
      <div class="fv-head">
        <div class="fv-logo">
          <nuxt-link to="/">
             <img src="~/assets/img/site-logo.png" alt="site-logo" >
          </nuxt-link>
        </div>
        <HamburgerMenuSection />
      </div>
      <div class="main-copy">
        <p class="main-copy-txt1">デザインで人を笑顔にする会社</p>
        <p class="main-copy-txt2">DIGSMILE INC.</p>
        <h1>
          DESIGN <br />
          FOR <br />
          SMILE.
        </h1>
      </div>
    </div>

    <div class="section-about">
      <div class="section-about-img">
        <img src="~/assets/img/about-img.png" alt="" />
      </div>
      <div class="section-about-txt">
        <h2 class="ttl">ABOUT US</h2>
        <p>
          DIGSMILEは、デザインで人を笑顔にする会社。<br />
          なんでもない日常に少しのワクワクと遊び心を提供します。笑顔には世界を変える力がある、デザインには人を幸せにする力がある。毎日に幸せを感じて生きていきたい。<br />
          DIGSMILEの社名にはそんな想いが込められています。
        </p>
        <nuxt-link to="/about">
           <a href="#" class="readmore">READ MORE</a>
        </nuxt-link>
      </div>
    </div>

    <div class="section-w-c">
      <div class="secion-work">
        <h2 class="ttl">WORK</h2>
        <img src="~/assets/img/daria-shevtsova-k_RYBedEvDw-unsplash.png" alt="" />
        <p>DIGSMILEの制作実績を紹介します。</p>
        <a href="#" class="readmore">PREPARING...</a>
      </div>

      <div class="secion-culture">
        <h2 class="ttl">CULTURE</h2>
        <img src="~/assets/img/culture-img.png" alt="" />
        <p>DIGSMILEの社内文化について紹介します。</p>
        <a href="#" class="readmore">PREPARING...</a>
      </div>
    </div>

    <div class="section-topics">
      <div class="section-topics-left">
        <h2 class="ttl">LATEST TOPICS</h2>
      </div>

      <div class="section-topics-center">
        <div class="section-topics-center-ch">
          <p>2020.02.01</p>
          <p class="topic-overview">
            イベントレポート「VRクリエイター座談会 〜5Gの次に来るもの〜」
          </p>
          <p>2020.01.18</p>
          <p class="topic-overview">プレスリリースのお知らせ DIGGIN’ RECORDS</p>
          <p>2020.01.01</p>
          <p class="topic-overview">新年明けましておめでとうございます</p>
        </div>
      </div>

      <div class="section-topics-right">
        <a href="#" class="readmore">PREPARING...</a>
      </div>
    </div>

    <div class="section-recruit">
      <div class="section-recruit-left">
        <h2 class="ttl">CONTACT</h2>
        <p>
          制作の依頼、取材の依頼、IRや採用についての連絡・お問い合わせはコンタクトページから承っております。<br />
          まずはお気軽にご連絡ください。担当者から改めて返信いたします。
        </p>
        <nuxt-link to="/contact">
          <a href="#" class="readmore">READ MORE</a>
        </nuxt-link>
      </div>

      <div class="section-recruit-right"></div>
      <img src="~/assets/img/recruit-img.png" alt="" />
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
  },
  head() {
    return {
      title: 'Cresta Home'
    }
  }
}
</script>

<style>

</style>
