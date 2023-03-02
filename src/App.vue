<script setup>
import Menu from './components/templates/Menu.template.vue'
import Main from './components/templates/Main.template.vue'
import Footer from './components/templates/Footer.template.vue'
</script>

<template>
  <body id="page-top">
    <!-- navBar -->
    <header>
      <Menu />
    </header>
  
    <main>
      <!-- <Main /> -->
      <Main />
    </main>

    <footer class="bg-dark ">
        <Footer />
    </footer>
  </body>
</template>


