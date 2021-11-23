<template>
  <div >
    <Header />
    <Main />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import Footer from "./components/Footer.vue"


export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style >
  h1 {
    text-align: center;
  }

  .container {
    width: 70%;
    margin: 0 auto;
    background-color: cornflowerblue;
  }
</style>
