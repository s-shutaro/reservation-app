<template>
  <div id="app">
  <Header />
  <Content/>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from 'vue-property-decorator';
import Header from '../components/Header.vue';
import Content from '../components/Content.vue';

@Component({
  components: {
    Header,
    Content
  }
})
export default class App extends Vue {}
</script>

<style src="../css/styles.css"></style>