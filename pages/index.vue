<template>
  <div class="ui container" v-html="text">
  </div>
</template>

<script setup lang="ts">
import path from 'path';
const { $loadMd } = useNuxtApp();

const text = $loadMd('/home/yc/Documents/code/ec3-gang.github.io/pages/index.md')
</script>