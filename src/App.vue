<script setup>
  import { RouterLink, RouterView } from 'vue-router'
  import Navigation from '@/components/NavigationView.vue'
  import FooterView from '@/components/FooterView.vue'
  
  import { library } from '@fortawesome/fontawesome-svg-core'
  import { faUserSecret } from '@fortawesome/free-solid-svg-icons'
  import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'

  import 'bootstrap';
  import 'bootstrap/dist/css/bootstrap.min.css';
  import 'jquery';
  import 'jquery-migrate';
  import 'animate.min.css';
  import 'ionicons-css';
</script>
<template>
  <Navigation />
  <RouterView />
  <FooterView />
</template>
<style>
  @import '@/assets/style.css';
  @import 'https://fonts.googleapis.com/css?family=Poppins:300,400,500,600,700';
</style>