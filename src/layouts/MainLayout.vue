<template>
  <div class="min-h-screen bg-gray-100">
    <Navbar/>

    <div class="max-w-7xl mx-auto px-4 py-6 grid grid-cols-12 gap-6">
      <!-- Left -->
      <div class="col-span-3">
        <LeftSidebar/>
      </div>

      <!-- Center -->
      <div class="col-span-6 space-y-4">
        <StoryBar/>
        <CreatePost/>
        <FeedPost/>
      </div>

      <!-- Right -->
      <div class="col-span-3">
        <RightSidebar/>
      </div>
    </div>
  </div>
</template>

<script setup>
import Navbar from '../components/Navbar.vue'
import LeftSidebar from '../components/LeftSidebar.vue'
import StoryBar from '../components/StoryBar.vue'
import CreatePost from '../components/CreatePost.vue'
import FeedPost from '../components/FeedPost.vue'
import RightSidebar from '../components/RightSidebar.vue'
</script>