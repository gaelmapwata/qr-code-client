<template>
  <div class="contain-menu">
    <v-container>
      <v-row>
        <v-col>
          <v-img
            :aspect-ratio="1"
            src="~/assets/images/menu.webp"
            height="390"
            contain
          />
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>
<script setup>
definePageMeta({
  auth: false
})
</script>
<style lang="scss">
.contain-menu{
  background-color: black;
}
</style>
