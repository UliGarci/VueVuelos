<template>
  <div>
     <b-breadcrumb :items="items"></b-breadcrumb>
     <p>SOY INICIO-LANDPAGE</p>
     <br>
     <b-nav vertical>
      <b-link :to="{name:'reserva-vuelo'}">Reservas de vuelo ⏭</b-link>
      <br>
      <b-link :to="{name:'vuelos-disponibles'}">Vuelos disponibles ⏭</b-link>
      <br>
      <b-link :to="{name:'vuelos-cancelados'}">Vuelos cancelados ⏭</b-link>
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
            href: '/inicio',
            active: true
          }
        ]
      }
    }
}
</script>

<style>

</style>