<template>
  <v-container class="body-menu">
    <div>
      <v-img
        :aspect-ratio="1"
        class="bg-white"
        src="~/assets/images/menu.webp"
        width="300"
        cover
      />
    </div>
  </v-container>
</template>
<script setup>
definePageMeta({
  auth: false
})
</script>
<style lang="scss">
</style>
