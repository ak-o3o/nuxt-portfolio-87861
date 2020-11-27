<template>
    <div class="fv-right">
      <button id="menu-open" @click="flag = true"><img src="~/assets/img/burger-menu.png" alt="burger-menu" ></button>
      <div id="menu-bg" :class="{open:flag}" @click="flag = false"></div>
      <!-- サイドバー -->
      <div class="sidebar">
        <nav id="menu-body" :class="{open:flag}">
          <button id="menu-close" @click="flag = false"><img src="~/assets/img/burger-menu-close.png" alt="closebtn"></button>
          <ul>
            <li v-for="menu in menus" v-if="menu.public">
              <nuxt-link :to="menu.href" v-html="menu.title">{{ menu.title }}</nuxt-link>
            </li>
          </ul>
        </nav>
      </div>
   </div>
</template>

<script>
export default {
     data() {
    return {
      flag: false,
      menus:[
        {public: true, href:'/', title:'HOME'},
        {public: true, href:'/about', title:'ABOUT US'},
        {public: true, href:'/contact', title:'CONTACT'},
        {public: false, href:'/blog', title:'Blog'},
        {public: false, href:'/culture', title:'Culture'},
        {public: false, href:'/work', title:'Work'},
      ]
    }
  },   
}
</script>