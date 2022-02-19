<template>
  <main class="grid">
    <aside class="container">
      <Sidebar />
    </aside>

    <article class="container">
      <Chat />
    </article>
  </main>
</template>

<script setup lang="ts">
import Sidebar from "@components/Sidebar.vue";
import Chat from "@components/Chat.vue";
</script>

<style scoped>
main {
  height: 100vh;
  width: 100vw;
}

.container {
  height: 100vh;
}

.grid {
  display: grid;
  grid-template-columns: 350px 1fr;
}
</style>