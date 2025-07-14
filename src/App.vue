<script setup></script>

<template>
  <header>
    <div class="wrapper">
      <img
        class="logo"
        src="https://sdmntprukwest.oaiusercontent.com/files/00000000-c500-6243-9a40-6dc1e31d6837/raw?se=2025-07-14T10%3A27%3A17Z&sp=r&sv=2024-08-04&sr=b&scid=b7599893-985b-5953-b707-344e24342bcd&skoid=b32d65cd-c8f1-46fb-90df-c208671889d4&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-07-14T08%3A37%3A51Z&ske=2025-07-15T08%3A37%3A51Z&sks=b&skv=2024-08-04&sig=ECHTJhxM8ILrI8s9BQ515L0baw2fmrfpyhiZgeG9XK8%3D"
      />
    </div>
  </header>

  <main></main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  padding: 0;
  display: block;
  margin: 0 auto;
  max-height: 100%;
  max-width: 100%;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
