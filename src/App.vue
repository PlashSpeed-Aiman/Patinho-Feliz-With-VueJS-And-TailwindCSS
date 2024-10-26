<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="bg-yellow-50 min-h-screen">
    <div class="container mx-auto px-4 py-8">
      <header class="text-center mb-12">
        <h1 class="text-4xl md:text-6xl font-bold text-yellow-600 mb-4">O Patinho Feliz 🦆</h1>
        <p class="text-xl text-yellow-700">Bem-vindo ao mundo do nosso amigo pato!</p>
      </header>

      <div class="max-w-4xl mx-auto bg-white rounded-lg shadow-xl p-8 mb-12">
        <div class="text-center mb-8">
          <div class="text-9xl waddle-animation duck-shadow float-animation inline-block mb-8">
            🦆
          </div>
          <h2 class="text-3xl font-bold text-yellow-600 mb-4">Sobre o Patinho</h2>
          <p class="text-lg text-gray-700 mb-4">
            Olá! Eu sou um patinho muito alegre que adora nadar e fazer novos amigos.
            Passo meus dias nadando no lago, brincando com outros patos e comendo
            deliciosas plantas aquáticas.
          </p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
          <div class="bg-yellow-100 p-6 rounded-lg">
            <h3 class="text-xl font-bold text-yellow-700 mb-3">Atividades Favoritas</h3>
            <ul class="list-disc list-inside text-gray-700">
              <li>Nadar no lago</li>
              <li>Fazer quack quack</li>
              <li>Comer pãozinho</li>
              <li>Tirar sonecas ao sol</li>
            </ul>
          </div>

          <div class="bg-yellow-100 p-6 rounded-lg">
            <h3 class="text-xl font-bold text-yellow-700 mb-3">Horário do Pato</h3>
            <ul class="list-disc list-inside text-gray-700">
              <li>6:00 - Acordar</li>
              <li>7:00 - Café da manhã</li>
              <li>12:00 - Natação</li>
              <li>15:00 - Soneca</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="text-center">
        <h2 class="text-2xl font-bold text-yellow-600 mb-4">Sons do Patinho</h2>
        <div class="inline-block bg-white p-6 rounded-lg shadow-md">
          <p class="text-gray-700 mb-4">Clique para ouvir o patinho:</p>
          <button
              class="bg-yellow-500 hover:bg-yellow-600 text-white font-bold py-3 px-6 rounded-full transition-all duration-300 transform hover:scale-105"
              onclick="alert('Quack! Quack! 🦆')">
            Fazer Quack! 🔊
          </button>
        </div>
      </div>

      <footer class="text-center mt-12 text-yellow-600">
        <p>© 2024 O Patinho Feliz - Todos os direitos reservados</p>
      </footer>
    </div>
  </div>
</template>

<style scoped>

</style>
