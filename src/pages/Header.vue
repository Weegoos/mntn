<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <q-layout
        view="hhh Lpr fFf"
        container 
        style="height: 70px; z-index: 1;"
        class="fixed"
    >
    <q-header class="text-white q-pt-sm bg-transparent">
        <q-toolbar>
          <div class="col">
            <q-btn label="MNTN"  flat/>
          </div>
         <div class="col-6 ">
            <q-btn no-caps label="Equipment"  flat/>
          <q-btn no-caps label="About us"  flat/>
          <q-btn no-caps label="Blog"  flat/>
         </div>
         <div class="col-2">
            <q-btn no-caps label="Account"  flat/>
         </div>
        </q-toolbar>
    </q-header>
    </q-layout>
  </div>
</template>

<script setup>
import { onMounted } from "vue";

onMounted(() => {
    console.log("Batyr");
})
</script>

<style>

</style>