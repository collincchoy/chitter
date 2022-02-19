<template>
  <main class="grid">
    <aside class="container">
      <TheSidebar />
    </aside>

    <article class="container">
      <ChatSection />
    </article>
  </main>
</template>

<script setup lang="ts">
import TheSidebar from "@components/TheSidebar.vue";
import ChatSection from "@components/ChatSection.vue";
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
