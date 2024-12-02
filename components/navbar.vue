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
      <a href="https://www.facebook.com/people/Atlantic-Tattoo-Art/61559306673874/" target="_blank">
        <LucideFacebook class="ico"/>
      </a>
      <a href="https://www.instagram.com/atlantic_ink/" target="_blank">
        <LucideInstagram class="ico"/>
      </a>
      <a href="https://www.google.com/maps/place/Atlantic+Tattoo+Art/@28.0522495,-16.7187311,970m/data=!3m2!1e3!4b1!4m6!3m5!1s0xc6a99fe8c803eff:0x69a83892a8126daf!8m2!3d28.0522448!4d-16.7161562!16s%2Fg%2F11y47lcqss?entry=ttu&g_ep=EgoyMDI0MTEyNC4xIKXMDSoASAFQAw%3D%3D" target="_blank">
        <LucideMapPinned class="ico"/>
      </a>
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