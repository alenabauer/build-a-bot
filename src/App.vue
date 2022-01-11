<template>
  <main>
    <HomePage />
  </main>
</template>

<script>
import HomePage from './components/HomePage.vue';

export default {
  name: 'App',
  components: {
    HomePage,
  },
};
</script>

<style>
body {
  background: linear-gradient(135deg, hsla(0, 0%, 100%, 1) 0%, hsla(0, 0%, 34%, 1) 100%);
  background-attachment: fixed;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
main {
  margin: 0 auto;
  background-color: white;
  width: 60%;
  padding: 32px;
}
</style>
