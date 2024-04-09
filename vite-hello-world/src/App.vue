<script>
export default {
  data() {
    return {
      AppTitle: 'La mia prima app con Vite!',
      cliccatore: 0
    }
  }
}
</script>

<template>
  <div>
    <h1 class="title">
      {{ AppTitle }}

    </h1>
    <div>
      <button @click="cliccatore++">
        clicca
      </button>
      <span class="spazio"> {{ cliccatore }}</span>
    </div>
  </div>
</template>

<style>
  .spazio {
    margin: 10px
  }
</style>