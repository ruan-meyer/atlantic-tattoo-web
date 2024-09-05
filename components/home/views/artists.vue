<template>
  <div class="flex items-center justify-center w-full">
    <h2 class="text-2xl font-bold">OUR ARTISTS</h2>
  </div>
  <div class="displayHorizontal father">
    <div class="child">
      <img src="~/assets/images/catia.jpg">
      <h2>Nameh Piercer</h2>
      <p>Body Piercer</p>
      <button>Portfolio</button>
    </div>
    <div class="child">
      <img src="~/assets/images/seba.jpg">
      <h2>Sebastian Suarez</h2>
      <p>Tattoo Artist</p>
      <button>Portfolio</button>
    </div>
  </div>
</template>

<style scoped>
  .father {
    justify-content: space-around;
  }
  .child{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  img {
    width: 24rem;
    height: 34rem;
  }
</style>
<script setup>
</script>