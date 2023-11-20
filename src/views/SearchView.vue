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

        <div class="grid xl:grid-cols-5 lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 gap-6">
            <CategorySelect category="Podcasts" image="https://picsum.photos/id/115/300/300" />
            <CategorySelect category="Reggae" image="https://picsum.photos/id/113/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/114/300/300" />
            <CategorySelect category="Made for you" image="https://picsum.photos/id/116/300/300" />
            <CategorySelect category="New Release" image="https://picsum.photos/id/117/300/300" />
            <CategorySelect category="Monday motivation" image="https://picsum.photos/id/118/300/300" />
            <CategorySelect category="Audiobooks" image="https://picsum.photos/id/119/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/120/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/121/300/300" />
            <CategorySelect category="New Release" image="https://picsum.photos/id/117/300/300" />
            <CategorySelect category="Monday motivation" image="https://picsum.photos/id/118/300/300" />
            <CategorySelect category="Audiobooks" image="https://picsum.photos/id/119/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/120/300/300" />
            <CategorySelect category="Rock" image="https://picsum.photos/id/121/300/300" />
        </div>
    </div>
</template>

