<template>
  <div id="app">
    <Home />
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';
import Home from '@/Home.vue';

@Component({
  components: {
    Home
  }
})
export default class App extends Vue {

}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
