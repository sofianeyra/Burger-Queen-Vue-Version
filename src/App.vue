<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
      <div class="container">
      <button type="button" class="btn btn-raised btn-primary">Primary</button>
      <button type="button" class="btn btn-raised btn-secondary">Secondary</button>
      <button type="button" class="btn btn-raised btn-success">Success</button>
      <button type="button" class="btn btn-raised btn-info">Info</button>
      <button type="button" class="btn btn-raised btn-warning">Warning</button>
      <button type="button" class="btn btn-raised btn-danger">Danger</button>
      <button type="button" class="btn btn-raised btn-link">Link</button>
      <button type="button" class="btn btn-raised active"><code>.active</code></button>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
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
