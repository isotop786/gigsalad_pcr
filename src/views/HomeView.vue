<template>
  <Hero/>
  <pages/>
  
</template>

<script>
// @ is an alias to /src
import Hero from "@/components/Hero.vue"
import Pages from "@/components/PageBox.vue"
export default {
  name: 'HomeView',
  components: {
    Hero,Pages
  }
}
</script>
