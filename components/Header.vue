<template>
  <div class="header">
    <el-row>
      <el-col :span="24">
        <h1>ヘッダー</h1>
      </el-col>
    </el-row>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class HeaderComponent extends Vue {}

</script>

<style src="../css/styles.css"></style>