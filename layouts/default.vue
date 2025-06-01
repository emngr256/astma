

<template>
    <header class="flex w-full items-center justify-between bg-gray-800 shadow-sm py-2 sticky top-0 z-50 text-white">
        <div class = "basis-1/4 items-center justify-start px-10">
            <img src="/assets/images/logo2.jpg" alt="Logo" class="h-12 w-12">
        </div>
        <div class="basis-1/4">
        </div>
        <nav class = "basis-1/2 flex flex-row items-center justify-end px-4 gap-4">
            <NuxtLink to="/" class = "my-auto p-2 hover:bg-gray-900">Home</NuxtLink>
            <NuxtLink to="/Lab3" class = "my-auto p-2 hover:bg-gray-900">Lab3</NuxtLink>
            <NuxtLink to="/login" class = "my-auto p-2 hover:bg-gray-900">Login</NuxtLink>
            <NuxtLink to="/logout" class = "my-auto p-2 hover:bg-gray-900">LogOut</NuxtLink>
        </nav>
    </Header>


  <main class = "p-5 flex-row w-full bg-[url(/assets/images/bg1.png)] h-screen">
        <slot />
  </main>

    <footer class = "flex flex-row w-full bg-gray-100 border-t-2 border-b-gray-400 items-center justify-center px-4 py-2 gap-4">
      <a href = "https://www.youtube.com/"><img src="assets/images/youtube.png" class = "w-16 h-16"></a>
      <a href = "https://github.com/emngr256/astma?tab=readme-ov-file"><img src="assets/images/github.png" class = "w-16 h-16"></a>
      <a href = "https://www.facebook.com/"><img src="assets/images/facebook.png" class = "w-16 h-16 bg-transparent"></a>
    </footer>
</template>

<!--#-->
<!--  <script setup>-->
<!--  import { usehead } from '#app';-->

<!--  usehead({-->
<!--    script: [-->
<!--      {-->
<!--        async:true,-->
<!--        src:-->
<!--      },-->
<!--      {-->
<!--        innerHTML:-->
<!--          window.datalayer = window.datalayer || [];-->
<!--          function gtag(){datalayer.push(arguments);}-->
<!--          gtag('js', new Date());-->
<!--          gtag('config', '');-->
<!--          ,-->
<!--          type: 'text/javascript',-->
<!--      },-->
<!--    ],-->
<!--    _dangerouslyDisableSanitizerByTagID: {-->
<!--      gtag: ['innerHTML'],-->
<!--    }-->
<!--  });-->
<!--  </script>-->
<!--#-->