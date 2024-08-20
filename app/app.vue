<template>
  <NuxtPage />
  <p class="text-center py-6 text-sm">
    <a href="https://github.com/atinux/my-pull-requests" target="_blank" class="text-gray-500 hover:text-gray-700 dark:text-gray-400 dark:hover:text-gray-300">Create my own contributions page.</a>
  </p>
</template>

<style lang="postcss">
body {
  @apply min-h-screen bg-white dark:bg-gray-900 text-gray-700 dark:text-gray-200 font-sans;
  transition: background-color 0.3s ease, color 0.3s ease;
}

/* ===== scrollbar ===== */
::-webkit-scrollbar {
  @apply w-3;
}

::-webkit-scrollbar-track {
  @apply bg-white dark:bg-gray-900;
  transition: background-color 0.3s ease;
}

::-webkit-scrollbar-thumb {
  background-color: rgb(234, 206, 219);
  transition: background-color 0.3s ease;
}

.dark ::-webkit-scrollbar-thumb {
  background-color: rgb(52, 63, 96);
  transition: background-color 0.3s ease;
}

::-webkit-scrollbar-thumb:hover {
  background-color: rgb(241, 186, 212);
  transition: background-color 0.3s ease;
}

.dark ::-webkit-scrollbar-thumb:hover {
  background-color: rgb(207, 145, 176);
  transition: background-color 0.3s ease;
}
</style>
