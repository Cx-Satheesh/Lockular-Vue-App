<template>
    <div class="w-full flex flex-col">
        <label class="text-[12px] mb-[7px] text-[#ffffff66]">{{label}}</label>
        <input class="shadow-inner h-[38px] bg-white px-[15px]" type="password" name="" :placeholder="placeholder">
    </div>
</template>

<script setup>
   defineProps(['label', 'placeholder'])
</script>
