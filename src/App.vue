<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <div class="flex flex-col w-screen h-screen bg-black text-2xl pl-5">
      <div class="flex p-3 flex-col bg-slate-500 w-fit rounded-2xl" >
        <!-- User Icon Subject Combo-->

        <div class="flex items:center gap-5">
          <div class="w-6 h-6 rounded-full bg-white"></div>
          <span class= "text-sm font-semibold" >You have mail!</span>
        </div>
        <div class="flex max-w-xs text-xs">
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorum reprehenderit nihil, minima a, aliquam maxime esse fugit assumenda perspiciatis, optio ullam! In reiciendis voluptate qui sint. Porro blanditiis nulla voluptatum?</p>
      </div>
      </div>
      
    </div>
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
