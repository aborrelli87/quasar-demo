<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-full.svg"
    >
    <div>{{prova}}</div>
  </q-page>
</template>

<script>
  export default {
    name: 'PageIndex',
    data () {
      return {
        // notice String as value
        prova: '16px'
      }
    }
  }
</script>
