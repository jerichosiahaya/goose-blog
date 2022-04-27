<template>
  <div class="flex flex-row justify-between">
      <img class="w-14 h-14 rounded-xl ml-5" src="https://cdn.britannica.com/06/88606-050-61656D23/Canada-goose.jpg" alt="">
      <div class="flex flex-row items-center text-lg font-medium">
          <span class="mr-5 hover:underline">Home</span>
          <span class="mr-5 hover:underline">Menu 1</span>
          <span class="mr-5 hover:underline">Menu 2</span>
      </div>
      <button class="bg-white mr-10 h-10 px-5 rounded-md mt-2 drop-shadow-md hover:shadow hover:drop-shadow-xl">
          Login
      </button>
  </div>
</template>

<script>
export default {
  name: 'MenuBar'
}
</script>
