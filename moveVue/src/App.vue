<template>
  <header class="flex items-center justify-center px-2 py-4">
    <router-link to="/">
      <h1 class="text-white text-3xl"><span class="text-green-500">Vue</span>Movies</h1>
    </router-link>
  </header>
  <main>
    <router-view />
  </main>
</template>
<style scoped>
body {
  background: #1f3044;
  color: aliceblue;
}

header {
  background: #18273a;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.1);
}
</style>