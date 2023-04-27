<template>
    <div class="container">
        <span class="label">Container Box</span>
        <content/>
    </div>
</template>

<script lang='ts' setup>
    import content from './content.vue';
</script>

<style lang='postcss' scoped>
    .container {
        @apply w-96 h-80 bg-gray-300 flex items-center justify-center relative;
    }

    .label {
       @apply absolute -top-3 px-3 left-0 bg-gray-300 text-black text-xs;
    }
</style>