<template>
  <div>
    <NavBar />
    <TheWelcome />
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import TheWelcome from './components/TheWelcome.vue'

export default {
  components: {
    NavBar,
    TheWelcome
  }
}
</script>

<style>
@import './assets/base.css';
@import './assets/main.css';
</style>
