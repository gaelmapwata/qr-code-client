<template>
  <v-container class="main-container">
    <v-row>
      <v-col class="title-menu">
        <h1>veuillez svp choisir le menu</h1>
      </v-col>
    </v-row>
    <div class="body-menu">
      <v-row>
        <v-col cols="12">
          <nuxt-link to="/page-drink">
            <v-btn
              color="primary"
              variant="flat"
              prepend-icon="mdi-gesture-double-tap"
            >
              Découvrez notre menu boissons
            </v-btn>
          </nuxt-link>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <nuxt-link to="/page-dish">
            <v-btn
              color="primary"
              variant="flat"
              prepend-icon="mdi-gesture-double-tap"
            >
              Découvrez  notre menu d'entré
            </v-btn>
          </nuxt-link>
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12">
          <v-btn
            color="primary"
            variant="flat"
            prepend-icon="mdi-gesture-double-tap"
          >
            Savourez  notre menu spécial
          </v-btn>
        </v-col>
      </v-row>
    </div>
  </v-container>
</template>

<script lang="ts" setup>
definePageMeta({
  auth: false
})
</script>
<style lang="scss">
.title-menu{
  text-align: center;
  font-weight: bold;
  color: white;
  border:2px solid blue;
  border-radius: 8px;
  margin: 15px;
}
.title-menu h1{
  font-size: 22px;
}
.body-menu {
  display: flex;
  flex-direction: column;
  justify-content: center; /* Centre verticalement */
  align-items: center; /* Centre horizontalement */
  margin-top: 100px;
  height: 20vh;  /*Exemple de hauteur pour centrer verticalement sur toute la page */
}
.main-container{
  margin: 0;
  height: 100vh;
  background-color: black;
}
</style>
