<template>
<el-calendar v-model="value">
</el-calendar>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Calender extends Vue {
    get value(){
        return new Date()
    }
}
</script>

<style src="../css/styles.css"></style>