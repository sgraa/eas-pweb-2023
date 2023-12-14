<template>
    <div>
      <div class="hero-section bg-gradient-to-l from-blue-950 to-purple-900 transition ease-in-out min-h-screen flex items-center justify-center space-x-9">
        <div class="w-1/3 px-4 mr-10">
          <img
            src="~/assets/belajar.png"
            alt="belajar cuy"
            class="w-900 h-900"/>
        </div>
        <div class="rounded-lg bg-blue-700 shadow-lg transition flex flex-col md:flex-row items-center md:w-1/3">
          <!-- Content Container -->
          <div class="md:w-full mx-auto px-2 sm:px-6">
            <div class="hero-content-inner p-10 pt-4 md:pt-16 pb-4 md:pb-10 text-center">
              <div class="hero-header pb-8 md:pb-10">
                <h1 class="text-4xl text-white md:text-6xl font-extrabold leading-tighter tracking-tighter mb-2">
                  Hello
                  <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-500 to-teal-400"
                    >and Welcome!</span
                  >
                </h1>
                <p class="text-lg text-white md:text-xlte xt-gray-600 mb-4">
                  Selamat datang anak-anak penerus bangsa! Harumkan sekolahmu dan daftar sekarang
                </p>
                <div class="hero-buttons max-w-xs mx-auto sm:max-w-none sm:flex sm:justify-center">
                  <NuxtLink to="/submission">
                    <button
                      type="button"
                      class="text-white text-lg bg-gradient-to-r from-purple-500 to-pink-500 hover:bg-gradient-to-l focus:ring-4 focus:outline-none focus:ring-purple-200 dark:focus:ring-purple-800 font-medium rounded-lg text-sm px-5 py-2.5 text-center me-2 mb-2"
                    >
                      Daftarkan Dirimu!
                    </button>
                  </NuxtLink>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  

<script setup>
</script>

