<template>
  <section class="w-full bg-white pt-7 pb-7 md:pt-20 md:pb-24">
    <div class="box-border flex flex-col items-center content-center px-8 mx-auto leading-6 text-black border-0 border-gray-300 border-solid md:flex-row max-w-7xl lg:px-16">
      <!-- Image -->
      <div class="box-border relative w-full max-w-md px-4 mt-5 mb-4 -ml-5 text-center bg-no-repeat bg-contain border-solid md:ml-0 md:mt-0 md:max-w-none lg:mb-0 md:w-1/2 xl:pl-10">
        <img src="~/assets/Plants.png" class="p-2 pl-6 pr-5 xl:pl-16 xl:pr-20 ">
      </div>

      <!-- Content -->
      <div class="box-border order-first w-full text-black border-solid md:w-1/2 md:pl-10 md:order-none">
        <h2 class="m-0 text-xl font-semibold leading-tight border-0 border-gray-300 lg:text-3xl md:text-2xl">
          Favorite Things About You
        </h2>
        <p class="pt-4 pb-8 m-0 leading-7 text-gray-700 border-0 border-gray-300 sm:pr-12 xl:pr-32 lg:text-lg">
          With your greatness and your flaws here are my most favorite thing about you.
        </p>
        <ul class="p-0 m-0 leading-6 border-0 border-gray-300">
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">✓</span></span> Your caring towards the people you love
          </li>
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">✓</span></span> Your Voice
          </li>
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">✓</span></span> All of your appearance, You're beatiful to me :3
          </li>
        </ul>
      </div>
      <!-- End  Content -->
    </div>
    <div class="box-border flex flex-col items-center content-center px-8 mx-auto mt-2 leading-6 text-black border-0 border-gray-300 border-solid md:mt-20 xl:mt-0 md:flex-row max-w-7xl lg:px-16">
      <!-- Content -->
      <div class="box-border w-full text-black border-solid md:w-1/2 md:pl-6 xl:pl-32">
        <h2 class="m-0 text-xl font-semibold leading-tight border-0 border-gray-300 lg:text-3xl md:text-2xl">
          The reasons
        </h2>
        <p class="pt-4 pb-8 m-0 leading-7 text-gray-700 border-0 border-gray-300 sm:pr-10 lg:text-lg">
          The reasons why I am interested in you and why did I love you. There are many but this is what I can think of
        </p>
        <ul class="p-0 m-0 leading-6 border-0 border-gray-300">
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">X</span></span> Its not because I can't live without you
          </li>
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">X</span></span> Its not because I can't do anything without you
          </li>
          <li class="box-border relative py-1 pl-0 text-left text-gray-500 border-solid">
            <span class="inline-flex items-center justify-center w-6 h-6 mr-2 text-white bg-yellow-300 rounded-full"><span class="text-sm font-bold">✓</span></span> Its because when I'm with you, everything in my life becomes better, even the bad things become not so bad
          </li>
        </ul>
      </div>
      <!-- End  Content -->

      <!-- Image -->
      <div class="box-border relative w-full max-w-md px-4 mt-10 mb-4 text-center bg-no-repeat bg-contain border-solid md:mt-0 md:max-w-none lg:mb-0 md:w-1/2">
        <img src="~/assets/Technologies.png" class="pl-4 sm:pr-10 xl:pl-10 lg:pr-32">
      </div>
    </div>
    <div class="relative flex flex-col justify-center md:flex-row md:space-x-4">
      <nuxt-link href="#_" to="/message-two" class="flex items-center w-full px-6 py-3 mb-3 text-lg text-white bg-purple-500 rounded-md md:mb-0 hover:bg-purple-700 md:w-auto">
        Next
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="w-5 h-5 ml-1"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <line x1="5" y1="12" x2="19" y2="12" />
          <polyline points="12 5 19 12 12 19" />
        </svg>
      </nuxt-link>
    </div>
  </section>
</template>

<script>
export default {
  name: 'MessageComponent'
}
</script>
