<script setup>
import LayoutView from '../components/layouts/LayoutView.vue';
import LoginView from './LoginView.vue';


</script>

<template>
  <div class="w-[100vw] h-[100vh] relative">
    <LayoutView />
    <img class="absolute top-0 left-0 w-full h-full object-cover" src="../assets/images/app-bg.png" alt="bg">
    <div class="relative px-[20px] sm:px-[50px] w-full h-full py-auto">
        <LoginView />
    </div><!--Container-->
  </div>  
</template>