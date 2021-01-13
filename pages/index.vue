<template>
  <div class="main text-center flex flex-col items-center justify-center">
    <Logo />
    <h1 class="title">GestionHSEQ</h1>
    <h2 class="subtitle">Seguridad, salud y medioambiente</h2>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo,
  },
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    }
  },
}
</script>
