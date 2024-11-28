<template>
  <footer
    class="mt-8 border z-10 border-t-[#33353F] border-l-transparent border-r-transparent text-white"
  >
    <div class="container p-12 flex justify-between items-center">
      <div class="text-white text-3xl font-bold">
        <a href="@/assets/logo.png">
          <img src="@/assets/logo.png" alt="logo" height="50" width="50" />
        </a>
      </div>
      <p class="text-slate-600">
        Copyright © {{ new Date().getFullYear() }} Faizal Mahmood
      </p>
    </div>
  </footer>
</template>
