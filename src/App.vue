<script setup>
import Menu from './components/templates/Menu.template.vue'
import Main from './components/templates/Main.template.vue'
import Footer from './components/templates/Footer.template.vue'
</script>

<template>
  <body id="page-top">
    <div>
      <!-- navBar -->
      <header>
        <Menu />
      </header>
    
      <main>
        <!-- <Main /> -->
        <Main />
      </main>
  
      <footer class="bg-dark d-flex justify-content-center aling-items-center" style="width: 100%; height: 100px;">
          <Footer />
      </footer>
    </div>
  </body>
</template>


