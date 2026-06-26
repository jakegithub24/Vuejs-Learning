<template>
  <HelloWorld msg="Hey Developer, welcome to Vue.js" />
  <HomeView />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomeView from './components/HomeView.vue';

export default {
  name: 'App',
  components: {
    HelloWorld, HomeView
  }
}
</script>
