<template>
  <div class="main text-center flex flex-col items-center justify-center">
    <logo />
    <h1 class="title">GestionHSEQ</h1>
    <h2 class="subtitle">Seguridad, salud y medioambiente</h2>
    <h3 class="subtitle">Software y asesorías</h3>
  </div>
</template>

<script>
import logo from '~/components/Logo.vue'

export default {
  components: {
    logo,
  },
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    }
  },
}
</script>
