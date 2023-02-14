<script lang="ts">
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    increaseCount() {
      this.count = this.count + 1
    }
  }
}
</script>

<template>
  <div>
    <button class="bg-orange-400 rounded-sm p-5" @click="increaseCount">Click me</button>
    <p>count is {{ count }}</p>
  </div>
</template>
