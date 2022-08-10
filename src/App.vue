<template>
  <div>
    <button @click="onJump('/')">首页</button>
    <button @click="onJump('/personal')">我的</button>
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  data() {
    return {
      name: '首页',
    }
  },
  methods: {
    onJump(type) {
      this.$router.push(type)
    },
  },
  mounted() {
    console.log(this.$router)
  },
  setup() {},
})
</script>
