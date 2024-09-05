<template>
 <div class="w-full flex row items-center justify-between">
    <div class="flex row justify-start">
      <a class="item" href="/">HOME</a>
      <a class="item" href="/">ABOUT</a>
      <a class="item" href="/">TATTOO</a>
      <a class="item" href="/">PIERCING</a>
      <a class="item" href="/">CONTACT</a>
    </div>
    <div class="flex row justify-end">
      <LucideFacebook class="ico"/>
      <LucideInstagram class="ico"/>
      <LucideMapPinned class="ico"/>
    </div>
 </div>
</template>

<style scoped>
  .item {
    padding: 1rem;
    font-weight: 600;
    font-size: 1.25rem;
  }
  .item:hover {
    color: aqua;
  }
  .ico {
    color: white;
    height: 25px;
    width: 25px;
    margin-left: 1rem;
  }
  .ico:hover {
    color: aqua;
  }

</style>
<script setup>
</script>