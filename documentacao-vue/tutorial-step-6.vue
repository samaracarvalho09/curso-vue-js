<script>
export default {
  data() {
    return {
      awesome: false
    }
  },
  methods: {
    toggle() {
      // ...
      this.awesome = !this.awesome
    }
  }
}
</script>

<template>
<div>
  <button @click="toggle">toggle</button>
  <h1 v-if="awesome">Vue is awesome!</h1>
  <h1 v-else>Oh no 😢</h1>
</div>
</template>