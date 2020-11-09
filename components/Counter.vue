<template>
  <div>{{ count }}</div>
</template>

<script lang="ts">
import Vue from 'vue'
export const a = 10
export default Vue.extend({
  data: () => ({ count: 0 }),
  methods: {
    add (x: string) {
      this.count += x
    }
  }
})
</script>
