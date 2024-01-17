<template>
  <div>
     <b-breadcrumb :items="items"></b-breadcrumb>
     <p>SOY LINEAS DE VUELO</p>
     <br>
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
          },
          {
            text: 'Lineas de vuelo',
            to: '/lineas-de-vuelo',
            active: true
          }
        ]
      }
    }
}
</script>

<style>

</style>