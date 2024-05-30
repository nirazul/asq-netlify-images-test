<script setup>
  const dyn = '/.netlify/images?url=/test.png&w100'
</script>

<template>
  <main>
    hello world
    <br>
    <br>
    original:
    <img style="width: 200px;" src="/test.png" alt="">

    converted:
    <img style="width: 200px;" :src="dyn" alt="">
  </main>
</template>

<style>
  main {
    display: flex;
    flex-flow: column nowrap;
  }

  img {
    display: block;
  }
</style>
