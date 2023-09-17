<template>
    <button class="border-0 bg-app-primary px-[15px] w-full h-[38px] uppercase font-semibold text-white flex items-center justify-between">
        <span>{{actionName}}</span>
        <img src="../../assets/icons/ic_action_arrow.svg" />
    </button>
</template>

<script setup>
    defineProps(['actionName'])
</script>
