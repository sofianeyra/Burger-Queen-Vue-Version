<template>
  <v-app>
    <v-toolbar color="#e95420" app>
      <Header/>
    </v-toolbar>
    <v-content>
      <Menu/>
    </v-content>
  </v-app>
</template>

<script>
import Header from './components/Header'
import Menu from './components/Menu'
export default {
  name: 'App',
  components: {
    Header,
    Menu
  },
  data () {
    return {
      //
    }
  }
}
</script>
