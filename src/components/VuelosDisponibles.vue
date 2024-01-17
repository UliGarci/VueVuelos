<template>
  <div>
     <b-breadcrumb :items="items"></b-breadcrumb>
     <p>SOY VUELOS DISPONIBLES</p>
     <br>
     <b-nav vertical>
      <b-link :to="{name:'lineas-de-vuelo'}">Lineas de vuelo ⏭</b-link>
     </b-nav>
  </div>
</template>

<script>
export default {
    data() {
      return {
        items: [
          {
            text: 'Inicio',
            to: '/inicio',
          },
          {
            text: 'Vuelos disponibles',
            to: '/vuelos-disponibles',
            active: true
          }
        ]
      }
    }
}
</script>

<style>

</style>