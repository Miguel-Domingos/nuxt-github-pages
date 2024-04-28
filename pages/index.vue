<template>
  <div class="flex flex-col justify-center items-center gap-4">
    <div class="w-full flex justify-between items-center">
      <span class="text-white text-xl">Home page</span>
      <span
        class="text-white text-xl cursor-pointer hover:text-green-400 transition"
        @click="navigateTo('/about')"
        >go to about</span
      >
    </div>
    <div class="w-full max-w-3xl">
      <img class="w-full object-cover" src="@/assets/deadpool.jpg" alt="" />
    </div>
  </div>
</template>
