<template>
  <header class="header">
    <div class="container">
      <div class="header-logo">
        <img  class="logo" src="../assets/MyLogo.png" alt="headerlogo">
        <h4 class="author">Maxim Saviuk</h4>
      </div>

      <div class="header-menu">
        <a class="menu--link" href="#">Про мене</a>
        <a class="menu--link" href="#">Походи</a>
        <a class="menu--link" href="#">Галерея</a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.header {
  width: 100vw;
  height: 50px;
  background-color: #1b2021;

}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1620px;
  margin: 0 auto;
}

.header-logo {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
}

.author {
  padding: 0 20px;
}

.logo {
  margin: 5px 0;
  height: 40px;
  width: 40px;
}

.menu--link {
  margin: 0 10px;
  text-decoration: none;
  color: aliceblue;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
