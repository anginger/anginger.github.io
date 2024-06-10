<template>
  <link
    href="https://fonts.googleapis.com/css?family=Abhaya+Libre:400,800|Montserrat:600|Alegreya+Sans:500&display=swap"
    rel="stylesheet">

  <main class="bg-white font-abhaya-libre relative">
    <header class="h-24 sm:h-32 flex items-center absolute top-0 right-0 z-20">
      <div class="container mx-auto px-6 sm:px-12 flex items-center justify-end">
        <nav class="flex items-center">
          <a href="/"
            class="hidden xl:block font-abhaya-libre uppercase text-gray-800 tracking-wider px-4 xl:px-8 py-2 text-lg hover:underline">
            首頁
          </a>
          <a href="#"
            class="hidden xl:block font-abhaya-libre uppercase text-gray-800 tracking-wider px-4 xl:px-8 py-2 text-lg hover:underline">
            關於
          </a>
          <a href="https://github.com/anginger" target="_blank"
            class="hidden xl:block font-abhaya-libre uppercase text-gray-800 tracking-wider px-4 xl:px-8 py-2 text-lg hover:underline">
            GitHub
          </a>
          <button class="ml-4 xl:ml-8 flex flex-col">
            <span class="w-8 h-1 bg-gray-800 mb-1 rounded"></span>
            <span class="w-8 h-1 bg-gray-800 mb-1 rounded"></span>
            <span class="w-8 h-1 bg-gray-800 mb-1 rounded"></span>
          </button>
        </nav>
      </div>
    </header>
    <div class="container mx-auto px-6 sm:px-12 flex flex-col sm:flex-row items-center relative z-10">
      <div class="sm:w-1/2 xl:w-2/6 flex flex-col items-start py-24 sm:py-0">
        <h1 class="text-6xl xl:text-10xl font-abhaya-libre text-fuchsia-900 font-bold leading-none mb-6">Anginger</h1>
        <h2 class="text-xl xl:text-3xl font-abhaya-libre text-fuchsia-900 uppercase font-bold leading-none tracking-widest -mt-2 mb-6">
          Platform
        </h2>
        <p class="xl:text-lg tracking-wider text-gray-700 font-alegraya-sans">
          為企業提供全方位資訊技術支援與系統規劃
        </p>
        <a href="#"
          class="font-montserrat text-white sm:font-xl uppercase py-3 px-6 sm:py-4 sm:px-8 rounded-full shadow-lg bg-fuchsia-900 hover:bg-fuchsia-800 mt-8 sm:mt-16">
          聯絡我們
        </a>
      </div>
      <div class="hidden sm:flex items-center justify-center xl:justify-end w-1/2 xl:w-4/6 py-32">
        <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="650pt" height="532pt"
          viewBox="0 0 470 532" version="1.2">
          <g id="surface47729">
            <path
              style="fill:none;stroke-width:5;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(88%,51.04%,75.4336%);stroke-opacity:1;stroke-miterlimit:10;"
              d="M 150 450 L 250 50 L 350 450 " />
            <path
              style="fill:none;stroke-width:5;stroke-linecap:round;stroke-linejoin:round;stroke:rgb(88%,51.04%,75.4336%);stroke-opacity:1;stroke-miterlimit:10;"
              d="M 150 450 L 50 250 L 450 250 " />
          </g>
        </svg>
      </div>
    </div>
  </main>
</template>
