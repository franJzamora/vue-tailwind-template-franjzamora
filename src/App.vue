<template>
  <div id="app">
    <!--     <HelloWorld msg="Welcome to Your Vue.js App"/>
 -->
    <section class="text-gray-700">
      <div class="container">
        <div class="flex-1 mx-auto">
          <div class="grid gap-4 grid-col-1 lg:grid-col-6 lg:gap-8">
            <div class="col-start-1 row-span-2 lg:col-span-1 col-span-full">
              <div
                class="flex flex-wrap h-full p-8 bg-gray-175 p-8 bg-gray-100 shadow-xl rounded-xl dark:bg-gray-900 xl:py-5 xl:px-10"
              >
                <div class="hidden w-full lg:block">
                  <img
                    class="inset-0 block object-cover object-center w-50 h-50 rounded-xl"
                    src="./assets/india-1-resized.jpeg"
                  />
                </div>
                <div
                  class="mt-auto mb-2 font-sans text-2xl font-black text-cyan-500"
                >
                  <h1>FranJZamora</h1>
                  <p class="text-sm leading-relaxed text-gray-400">
                    Front-End Developer
                  </p>
                  <p
                    class="mt-4 leading-relaxed tracking-tighter text-md dark:text-gray-100"
                  >
                    Multimedia Engineer from Murcia, Spain. In love with technology... 
                  </p>
                </div>
              </div>
            </div>
            <div class="lg:col-start-2 lg:col-span-4 col-span-full">
              <div
                class="flex flex-wrap h-full p-8 bg-gray-175 p-8 bg-gray-100 shadow-xl rounded-xl dark:bg-gray-900 xl:py-5 xl:px-10"
              >
              <div class="w-full p-6 text-left xl:w-2/3">
                <div
                  class="mt-auto mb-2 font-sans text-2xl font-black text-cyan-500 grid grid-cols-3 gap-4"
                >
                  <!-- logo twitter -->
                  <div>
                   <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-twitter" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                    <path d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c-.002 -.249 1.51 -2.772 1.818 -4.013z" />
                  </svg>
                  </div>
                  <!-- logo instagram -->
                  <div>
                   <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                      <rect x="4" y="4" width="16" height="16" rx="4" />
                      <circle cx="12" cy="12" r="3" />
                      <line x1="16.5" y1="7.5" x2="16.5" y2="7.501" />
                    </svg>
                  </div>
                  <div>
                    <!--  logo linkedin -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-linkedin" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                      <rect x="4" y="4" width="16" height="16" rx="2" />
                      <line x1="8" y1="11" x2="8" y2="16" />
                      <line x1="8" y1="8" x2="8" y2="8.01" />
                      <line x1="12" y1="16" x2="12" y2="11" />
                      <path d="M16 16v-3a2 2 0 0 0 -4 0" />
                    </svg>
                  </div>
                  <div>
                    <!--  logo email -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-mail" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                      <rect x="3" y="5" width="18" height="14" rx="2" />
                      <polyline points="3 7 12 13 21 7" />
                    </svg>
                  </div>
                  <div>
                    <!--  logo telegram -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-telegram" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                      <path d="M15 10l-4 4l6 6l4 -16l-18 7l4 2l2 6l3 -4" />
                    </svg>
                  </div>
                  <div>
                    <!--  logo github -->
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github" width="44" height="44" viewBox="0 0 24 24" stroke-width="1.5" stroke="#3930EF" fill="none" stroke-linecap="round" stroke-linejoin="round">
                      <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                      <path d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5" />
                    </svg>
                  </div>
                </div>
              </div>
              </div>
            </div>
            <div
              class="lg:col-start-2 col-span-full col-span-full border-4 border-light-blue-500"
            >
              <p>Hola</p>
            </div>
            <div
              class="lg:col-end-7 col-span-full lg:col-span-1 border-4 border-light-blue-500"
            >
              <p>Hola</p>
            </div>
            <div
              class="lg:col-start-2 col-span-full lg:col-span-2 border-4 border-light-blue-500"
            >
              <p>Hola</p>
            </div>
            <div
              class="row-span-2 lg:col-end-7 col-span-full lg:col-span-3 border-4 border-light-blue-500"
            >
              <p>Hola</p>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */

export default {
  name: "App",
  components: {
    /*  HelloWorld, */
  },
};
</script>

<style>
</style>
