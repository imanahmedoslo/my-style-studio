<template>
  <div class="flex flex-col">
    <Header />
    <CartView />
    <RouterView />
    <Footer />
  </div>
</template>

<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'
import CartView from '@/views/CartView.vue'

</script>