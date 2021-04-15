<template>
  <div id="app">
    <Header/>
  </div>
</template>

<script>
import Header from './components/Header.vue';

export default {
  name: 'App',
  components: {
    Header,
  },
  data: () => ({
    firstName: 'Maxim Saviuk',
    num: '2',
  }),
};
</script>

<style lang="scss">
*{
  margin: 0;
}

body {
  background-color: #151515;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #e0e0e0;
}
</style>
