<template>
  <div>
    <div>
      <Header />
    </div>
    <div>
      <router-view />
    </div>
  </div>
</template>

<script setup>
import Header from './pages/Header.vue';
defineOptions({
  name: 'App'
});
</script>
