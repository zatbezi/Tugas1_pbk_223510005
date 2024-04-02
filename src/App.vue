<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <!-- Ubah src untuk menunjuk ke gambar yang ingin Anda tambahkan -->
    <img
      alt="Foto"
      class="foto"
      src="@/assets/image/os3b_dccv_140923-removebg-preview.png"
      width="300"
      height="200"
    />

    <div class="wrapper">
      <HelloWorld msg="Hi it's me Azizi" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

/* Ganti .logo dengan .foto */
.foto {
  display: block;
  margin: 0 auto;
  height: 300px;
  widht: 400px;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

</style>
