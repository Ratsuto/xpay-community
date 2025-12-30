<template>
  <div class="bg-white rounded-xl shadow p-4 space-y-4">
    <h3 class="font-semibold">Who to follow</h3>

    <div v-for="i in 4" :key="i" class="flex items-center justify-between">
      <div class="flex items-center gap-3">
        <img class="w-8 h-8 rounded-full" src="https://i.pravatar.cc/40"/>
        <div>
          <p class="text-sm font-medium">User {{ i }}</p>
          <p class="text-xs text-gray-400">Web Developer</p>
        </div>
      </div>
      <button class="text-primary font-bold">+</button>
    </div>
  </div>
</template>
