<template>
  <div>
    <div class="overlay-background"></div>
    <div class="game">
      <Header/>
      <router-view/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Header from './components/Header'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
  .overlay-background {
    width: 100%;
    height: 100%;
    position: fixed;
    top: 0;
    left: 0;
    z-index: 1;
    background-image: url(/images/bg.png);
    background-position: center;
    background-size: contain;
  }
  .game {
    position: relative;
    z-index: 2;
  }
  body, div, p {
    margin: 0;
    padding: 0;
  }
  html {
    font-family: ProximaNova,-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  }
</style>
