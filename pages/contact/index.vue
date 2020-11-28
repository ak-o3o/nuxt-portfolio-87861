<template>
  <div class="container">
    <div class="fv-contact">
      <div class="fv-head">
        <div class="fv-logo">
          <nuxt-link to="/">
             <img src="~/assets/img/site-logo.png" alt="site-logo" />
          </nuxt-link>
        </div>
        <HamburgerMenuSection />
      </div>
      <div class="main-copy">
        <h1>CONTACT</h1>
        <p class="main-copy-txt1">お問合わせ</p>
      </div>
    </div>

    <div class="contact">
      <div class="contact-form">
        <p class="form-info">
          ご依頼やご相談についてのご質問やご要望がございましたら、下記フォームよりお気軽にお問い合わせください。送付いただいた内容を確認の上、担当者からご連絡させていただきます。
        </p>
        <form>
            <p>問い合わせ種別 <span> 必須</span></p>
            <div class="form-radio">
              <input type="radio" id="01-A" name="form-type" value="request" /> <label for="01-A" class="radio01">制作依頼 </label>
              <input type="radio" id="01-B" name="form-type" value="adoption" /> <label for="01-B" class="radio01">採用</label>
              <input type="radio" id="01-C" name="form-type" value="ir" /><label for="01-C" class="radio01"> IR</label>
              <input type="radio" id="01-D" name="form-type" value="other" /><label for="01-D" class="radio01"> その他</label>
            </div>

            <p>会社名・団体名</p>
            <input class="form-txt-area" type="text" />
            <p>お名前 <span> 必須</span></p>
            <input class="form-txt-area" type="text" />
            <p>メールアドレス <span> 必須</span></p>
            <input class="form-txt-area" type="text" />
            <p>電話番号</p>
            <input class="form-txt-area" type="text" />
            <p>お問合せ内容 <span> 必須</span></p>
            <textarea class="form-txt-area" name="" id="" cols="30" rows="10"></textarea>

            <h2 class="ttl">PRIVACY POLICY</h2>
            <textarea name="" id="" cols="30" rows="10">
    個人情報保護方針
    株式会社DIGSMILE（以下、当社）では、個人情報の重要性を認識し、
    以下の基準に従って、適切な管理、保護に努めます。
    
    1.個人情報の収集、利用
    当社では、お客様との取引、サービスの提供のために個人情報を適法に収集し、
    収集した目的の範囲内で、個人情報を利用いたします。

    2.個人情報の第三者への開示と提供
    収集したお客様の個人情報は、法的な要請等によらない限り、お客様の承諾を
    得ない第三者に対して提供・開示はいたしません。業務の都合上、業務委託先に
    個人情報を提供する場合は、機密保持契約等によって業務委託先に個人情報保護
    を義務付けるとともに、業務委託先が適切に個人情報を取り扱うように管理いたします。
            </textarea>
            <div class="form-under">
              <input type="checkbox" id="01-E" name="checkbox01" />
              <label for="01-E" class="checkbox01" >個人情報の取り扱いについて同意のうえ送信します。</label>

              <p><input type="submit" value="送信" class="readmore" /></p>
            </div>
          </form>
      </div>
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
      title: 'Cresta Contact'
    }
  }
}
</script>

<style>
</style>
