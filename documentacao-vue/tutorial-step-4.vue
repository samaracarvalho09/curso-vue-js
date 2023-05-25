<script>
export default {
  data() {
    return {
      count: 0,
      bgContainer: 'container'
    }
  },
  methods: {
    increment() {
      this.count++
    },
    decrement() {
			this.count--
    }
  }
}
  
</script>

<template>
  <!-- make this button work -->
 
  <div v-bind:class="bgContainer">
      <button v-on:click="decrement">-</button>
   <div>
    {{ count }}
  </div>
  <button v-on:click="increment">+</button>
  </div>

</template>

<style>
  
.container {
  display: flex;
  gap: 20px;
  align-items: center;
  font-weight: 700;
}
  
button {
    width: 50px;
    height: 30px;
}
  
</style>