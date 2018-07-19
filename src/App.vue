<template>
  <div id="app">
    
    <Header title="This is the Header"></Header>
    <Banner title="This is banner"> </Banner>
    <About title="This is About Section"> </About>
    <Projects title="This is Projects Section"> </Projects>
  
  </div>
</template>

<script>
import Header from './components/Header/Header.vue'
import Banner from './components/Banner/Banner.vue'
import About from './components/About/About.vue'
import Projects from './components/Projects/Projects.vue'

export default {
  name: 'app',
  components: {
    Header,
    Banner,
    About,
    Projects
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
