<template>
  <div class="bg-white p-4 rounded-xl shadow flex gap-4 overflow-x-auto">
    <div
        v-for="i in 6"
        :key="i"
        class="min-w-[80px] h-32 rounded-xl bg-gray-200 flex items-center justify-center text-sm font-semibold"
    >
      Story {{ i }}
    </div>
  </div>
</template>
