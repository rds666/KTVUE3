<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import { defineComponent } from 'vue'
import TheWelcome from '@/components/TheWelcome.vue'

export default defineComponent({
  name: 'About',

  setup() {
    console.log('About')
  }
})
</script>

<style>
</style>
