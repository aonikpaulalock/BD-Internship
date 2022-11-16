<script setup>
import Navber from './components/Navber.vue'
import Main from './components/Main.vue'
import Aside from './components/Aside.vue'
</script>
<template>
  <section class="dashboard-container">
    <header class="header-container">
      <Navber></Navber>
      <Main></Main>
    </header>
    <Aside></Aside>
  </section>
</template>