<template>
  <!-- Main Hero Content -->
  <div class="container max-w-lg px-4 py-32 mx-auto text-left md:max-w-none md:text-center">
    <h1 class="text-5xl font-extrabold leading-10 tracking-tight text-left text-gray-900 md:text-center sm:leading-none md:text-6xl lg:text-7xl">
      <span class="inline md:block">For</span> <span class="relative mt-2 text-transparent bg-clip-text bg-gradient-to-br from-indigo-600 to-indigo-500 md:inline-block">Rachmi</span>
    </h1>
    <div class="mx-auto mt-5 text-gray-500 md:mt-12 md:max-w-lg md:text-center lg:text-lg">
      For the greatest thing that has ever happened to me, for my 💙 Rachmi 💙 and our memories
    </div>
    <div class="flex flex-col items-center mt-12 text-center">
      <span class="relative inline-flex w-full md:w-auto">
        <NuxtLink to="/second">
          <a href="#_" type="button" class="inline-flex items-center justify-center w-full px-8 py-4 text-base font-bold leading-6 text-white bg-indigo-600 border border-transparent rounded-full md:w-auto hover:bg-indigo-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-600">
            Start
          </a>
        </NuxtLink>
      </span>
      <a href="https://youtu.be/xCx1eSdkyr0" target="_blank" rel="noreferrer" class="mt-3 text-sm text-indigo-500">Play our song</a>
    </div>
  </div>
  <!-- End Main Hero Content -->
</template>

<script>
export default {
  name: 'MainHero'
}
</script>
