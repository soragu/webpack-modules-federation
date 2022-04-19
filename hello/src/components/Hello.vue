<template>
  <div>Hello! <world /></div>
</template>

<script>
import { defineAsyncComponent } from 'vue'

export default {
  name: 'Hello',
  components: {
    World: defineAsyncComponent(() => import('WorldApp/World'))
  },
  setup() {},
}
</script>
