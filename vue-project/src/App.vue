<template>
  <div id="app">
    <HeaderComponent></HeaderComponent>
    <HomePageBanner></HomePageBanner>
    <HomePageProject></HomePageProject>
    <HomePageCounter></HomePageCounter>
    <HomePageArticles></HomePageArticles>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
import HeaderComponent from './components/HeaderComponent.vue'
import HomePageBanner from './components/pages/HomePage/HomePageBanner.vue'
import HomePageProject from './components/pages/HomePage/HomePageProject.vue'
import HomePageCounter from './components/pages/HomePage/HomePageCounter.vue'
import HomePageArticles from './components/pages/HomePage/HomePageArticles.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent,
    HomePageBanner,
    HomePageProject,
    HomePageCounter,
    HomePageArticles,
    FooterComponent
  }
}
</script>

<style lang="scss">
$widthSite: 1200px;

* {
   margin: 0;
   padding: 0;
}

a {
   text-decoration: none;
}

.center {
   padding-left: calc(50% - $widthSite / 2);
   padding-right: calc(50% - $widthSite / 2);
}
</style>
