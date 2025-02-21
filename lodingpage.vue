
<template>
    <div class="min-h-screen bg-gray-100 flex flex-col items-center justify-center">
      <header class="w-full p-5 bg-white shadow-md flex justify-between items-center">
        <h1 class="text-2xl font-bold">My Landing Page</h1>
        <nav>
          <ul class="flex gap-4">
            <li><a href="#about" class="text-blue-500 hover:underline">About</a></li>
            <li><a href="#services" class="text-blue-500 hover:underline">Services</a></li>
            <li><a href="#contact" class="text-blue-500 hover:underline">Contact</a></li>
          </ul>
        </nav>
      </header>
      
      <main class="flex flex-col items-center text-center py-20">
        <h2 class="text-4xl font-extrabold text-gray-900">Welcome to My Vue Landing Page</h2>
        <p class="text-gray-600 mt-4">We create stunning web experiences with Vue.js.</p>
        <button class="mt-6 px-6 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600">
          Get Started
        </button>
      </main>
      
      <footer class="w-full p-5 bg-white shadow-md text-center">
        <p class="text-gray-600">&copy; 2025 My Landing Page. All rights reserved.</p>
      </footer>
    </div>
  </template>
  
  <script>
  export default {
    name: "LandingPage",
  };
  </script>
  
  <style scoped>
  /* Custom styles if needed */
  </style>
