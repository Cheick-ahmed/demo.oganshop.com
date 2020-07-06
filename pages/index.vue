<template>
  <div class="py-10 sm:py-12">
    <div class="text-center">
      <nuxt-link :to="{ name : '' }" class="text-5xl lg:text-6xl font-extrabold font-comfortaa">
        OganShop
      </nuxt-link>
    </div>
    <div class="mt-12 xl:mt-16 grid lg:grid-cols-3 gap-4 row-gap-12">
      <div class="bg-white py-4" v-for="x in 16">
        <div class="flex items-center justify-between px-6">
          <span class="uppercase font-light text-sm">OganShop</span>
          <div class="flex items-center">
            <span class="flex items-center justify-center shadow-outline-blue h-1 w-1 rounded-full p-1">
              <span class="text-2xl text-gray-600">&middot;</span>
            </span>
            <span class="ml-4 flex items-center justify-center h-1 w-1 rounded-full p-1">
              <span class="text-2xl text-gray-400">&middot;</span>
            </span>
            <span class="ml-4 flex items-center justify-center h-1 w-1 rounded-full p-1">
              <span class="text-2xl text-gray-400">&middot;</span>
            </span>
          </div>
        </div>
        <div>
          <img src="~assets/images/12.png" class="h-72 w-full object-cover" alt="">
        </div>
        <div class="px-6 font-bold text-sm font-comfortaa">
          Mint
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    head () {
      return {
        title : 'OganShop'
      }
    }
  }
</script>


