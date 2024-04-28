<template>
  <div class="flex flex-col justify-center items-center gap-4">
    <div class="w-full flex justify-between items-center">
      <span class="text-white text-xl">about page</span>
      <span
        @click="navigateTo('/')"
        class="text-white text-xl cursor-pointer hover:text-green-400 transition"
        >go to home</span
      >
    </div>
    <div class="w-full max-w-3xl">
      <img class="w-full object-cover" src="@/assets/spider-man.jpg" alt="" />
    </div>
  </div>
</template>
