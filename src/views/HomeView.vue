<script>
  export default {
    name: "HomeView",
    data(){
      return {
        url: "https://avatars.githubusercontent.com/u/583231?v=4",
      }
    }
  }
</script>

<template>
  <main>
    <div class="container">
      <h1 class="display-3">Bienvenidos a la Galería Github</h1>
      <img :src="url" class="h-25 round rounded-circle" alt="Octocat">
    </div>
  </main>
</template>
