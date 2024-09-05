<template>
  <div class="header">
    <Navbar />
    <div class="class pt-4">
      <p class="text-5xl font-bold">WELCOME TO</p>
      <p class="text-8xl font-bold">ATLANTIC</p>
      <p class="text-4xl font-bold">TATTOO STUDIO</p>
      <div class="pt-4 flex justify-center w-full">
        <button class="text-xl mr-1">Tattoo</button>
        <button class="text-xl ml-1">Piercing</button>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .class {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding: 10rem;
  }
  .header {
    background-image: url("~/assets/images/store.jpg");
    padding-bottom: 5rem;
    background-repeat: no-repeat;
    background-size: cover;
    background-position-x: center;
  }
</style>
<script setup>
</script>