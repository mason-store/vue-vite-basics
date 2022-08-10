<template>
  <h1>{{ msg }} [home.vue]</h1>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Home',
  data() {
    return {
      msg: 'Hello Vue 3.0 + Vite!',
    }
  },
  setup() {},
})
</script>
