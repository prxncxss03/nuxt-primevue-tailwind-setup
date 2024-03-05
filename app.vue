<script setup>
  useHead ({
    meta: [
      {
        name: 'viewport',
        content: 'width=device-width, initial-scale=1.0'
      },
    ],
    link: [
      {
        rel: 'stylesheet',
        href: "http://fonts.cdnfonts.com/css/sf-pro-display"
      }
    ]
  })
</script>

<template >
  <div class="font-sf">
    <NuxtPage/>
  </div>
</template>


<style>
  @import url('/assets/css/global.css');
</style>