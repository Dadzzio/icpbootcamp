<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo">

    <h1><i>Dzień dobry witam państwa w moim pierwszym projekcie na BOOTCAMP!</i></h1>
    <br>
    <button @click="podbij">Kliknij mnie!!!!</button>
    <p>{{ licznik }}</p>
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik:0
    }
  },
  methods: {
    podbij() {
      this.licznik++
    }
  }
}
</script>