<template>
  <main>
    <TheWelcome />
  </main>
</template>

<script>
import { defineComponent } from 'vue'
import TheWelcome from '@/components/TheWelcome.vue'

export default defineComponent({
  name: 'Home',

  components: {
    TheWelcome,
  },

  setup() {
    console.log('Home')
  }
})
</script>

<style>
</style>
