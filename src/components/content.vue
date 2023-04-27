<template>
   <div class="content">
      <span class="label">Content Box</span>
   </div>
</template>

<script lang='ts' setup>
    
</script>

<style lang='postcss' scoped>
   .content  {
      @apply bg-black h-24 w-36 relative;
   }
 .label {
       @apply absolute -top-3 px-3 left-0 bg-black text-white text-xs
    }
</style>