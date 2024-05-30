<template>
  <v-container class="main-container">
    <v-row class="row-img">
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
</template>
<script setup>
definePageMeta({
  auth: false
})
</script>
<style lang="scss">
.main-container{
  height: 100vh;
  background-color: black;
}
.row-img{
  margin-top: 100px !important;
}
</style>
