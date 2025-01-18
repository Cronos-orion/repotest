<script>
  import { ref } from 'vue';

  const counter = ref(0)

  function counterChange() {
    counter.value++
    console.log(counter)
  }


</script>

<template>
  <h1>
    Olá Mundo!
  </h1>
  <button @click="counterChange">
    Click
  </button>
  <div class="result">
    Result: {{ counter }}
  </div>
</template>


<style scoped>
</style>