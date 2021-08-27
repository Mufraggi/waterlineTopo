<template>
  <div class="content">
    <div class="picture">
      <nuxt-img
          src="/images/mainPage.jpg"
          sizes="sm:100vw md:50vw lg:100%"
      />
      </div>
      <div class="callAction">
        <h2>Retrouver tout les spots de Waterline<br>
          dans<br>
          les Alpes-Maritimes</h2>
        <div class="button">
          <b-button to="/spot" size="lg" variant="outline-primary">Accéder à la liste des spot</b-button>
          <b-button size="lg" variant="outline-info">Faire une demande d'ajout</b-button>
        </div>
      </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped>

.content{
  margin-top: 20px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
.callAction {
  margin:  0 auto;
  text-align: center;
  padding-top: 12.5%;
}
.picture {
}
.button{
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-evenly;
  display: inline-flex;
  gap: 5px
}

</style>
