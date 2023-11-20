<script setup>
import CategorySelect from '../components/CategorySelect.vue';

</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer">
            Recommanded Radio
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <CategorySelect category="Podcasts" image="https://picsum.photos/id/112/300/300" />
        </div>
    </div>
</template>

