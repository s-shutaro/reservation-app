<template>
  <div class="content">
    <Calender />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Calender from './Calender.vue'

@Component({
  components:{
    Calender
  }
})
export default class Content extends Vue {}
</script>

<style src="../css/styles.css"></style>