<!-- To override hero image -->
<script setup lang="ts">
import DefaultTheme from 'vitepress/theme';

const { Layout } = DefaultTheme;
</script>

<template>
  <Layout>
    <template #home-hero-image>
      <img id="hero-image" src="/080104.png">
    </template>
  </Layout>
</template>

<style scoped>
img#hero-image {
  position: relative;
  min-width: 120%;
  height: auto;
  left: -70px;
  -webkit-mask-image: linear-gradient(to right, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 1) 100%);
  mask-image: linear-gradient(to right, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 1) 100%);
}
</style>
