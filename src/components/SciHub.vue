<script>
export default {
  data() {
    return {}
  }
}
</script>

<template>
<div class="flex flex-row justify-center">
  <!-- left -->
  <div class="container">
    <!-- logo -->
    <div class="flex flex-row items-center justify-center"> 
      <img src="https://sci-hub.se/pictures/ravenround_hs.gif" alt="logo">
      <p class="text-[#8b0000] text-8xl font-serif">sci-hub</p>
    </div>

     <!-- search bar -->
    <div class="flex flex-row  items-center justify-center box-content h-14 space-x-1 bg-slate-200">
      <input class="h-10 w-96 px-2 border text-xl" type="text" placeholder="enter your reference"/>
      <button class="h-10 w-32 border bg-red-800 text-white">open</button>
    </div>

    <div class="flex justify-center h-10">
      <div class="flex flex-row items-center space-x-6">
        <button class="text-xl text-slate-500 font-serif">database</button>
        <button class="text-xl text-slate-500 font-serif">about</button>
        <button class="text-xl text-slate-500 font-serif">Elbakyan</button>
        <button class="text-xl text-slate-500 font-serif">stats</button>
        <button class="text-xl text-slate-500 font-serif">donate</button>
      </div>
    </div>
  </div>
</div>
</template>