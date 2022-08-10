<template>
  <div>
    <h1>名称：{{ userName }}</h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
export default defineComponent({
  name: 'personal',
  setup() {
    const userName = 'mason'
    return { userName }
  },
})
</script>
