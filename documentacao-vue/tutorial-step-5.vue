<script>
export default {
  data() {
    return {
      text: ''
    }
  },
  methods: {
    onInput(e) {
      this.text = e.target.value
    }
  }
}
</script>

<template>
  <div>
    <input :value="text" @input="onInput" placeholder="Type here">
    <p>{{ text }}</p>
  </div>
</template>

<!-- OUTRA FORMA -->


<!-- <template>
  <div>
    <input v-model="text" placeholder="Type here">
    <p>{{ text }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: ''
    }
  }
}
</script> -->