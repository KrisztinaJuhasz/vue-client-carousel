<script setup>
import CarouselItems from './CarouselItems.vue';
</script>

<template>
    <div class="bg-slate-600 py-10 overflow-x-clip">
        <div class="flex flex-row self-start justify-start items-baseline animate-carousel hover:animate-pause">
            <CarouselItems />
            <CarouselItems />
            <CarouselItems />
        </div>
    </div>
</template>
