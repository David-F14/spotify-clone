<script setup>
    import HomeCard from '../components/HomeCard.vue';
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
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/75/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/85/300/300" title="Title is here" subTitle="subtitle" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer">
            Recommanded Songs
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="https://picsum.photos/id/30/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard image="https://picsum.photos/id/45/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="md:block hidden" image="https://picsum.photos/id/65/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="lg:block hidden" image="https://picsum.photos/id/75/300/300" title="Title is here" subTitle="subtitle" />
            <HomeCard class="xl:block hidden" image="https://picsum.photos/id/85/300/300" title="Title is here" subTitle="subtitle" />
        </div>
    </div>
</template>