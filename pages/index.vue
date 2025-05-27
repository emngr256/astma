<template>
    <header class="flex w-full items-center justify-between bg-pink-800 shadow-sm py-2 sticky top-0 z-50 text-white">
        <div class = "basis-1/4 items-center justify-start px-10">
            <img src="/assets/images/5050.png" alt="Logo" class="h-12 w-12">
        </div>
        <div class="basis-1/4">
        </div>
        <nav class = "basis-1/2 flex flex-row items-center justify-end px-4 gap-4">
            <NuxtLink to="/" class = "my-auto p-2 hover:bg-pink-900">Home</NuxtLink>
            <NuxtLink to="/Lab3" class = "my-auto p-2 hover:bg-pink-900">Lab3</NuxtLink>
            <NuxtLink to="/contact" class = "my-auto p-2 hover:bg-pink-900">Login</NuxtLink>
            <NuxtLink to="/login" class = "my-auto p-2 hover:bg-pink-900">LogOut</NuxtLink>    
        </nav>
    </Header>
    <main class="flex flex-col items-center justify-center h-screen bg-white-900">
        <h1 class="text-4xl font-bold mb-4" style="color: black;">Welcome to my site</h1>
        <p class="text-lg"  style="color: black;">:)</p>
    </main>
</template>