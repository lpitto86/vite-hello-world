<script>
/* Importazione del componente */

export default {
  data() {
    return { 
      count: 0 
    }
  },
  methods: {
    incrementCount () {
      this.count++
    }
  }
}
</script>

<template>
  <div>
    <h1>
      {{ count }}
    </h1>
    <button @click="incrementCount()">
      Incrementa counter
    </button>
  </div>
</template>

<style scoped>
h1 {
  color: lightcoral;
}
</style>
