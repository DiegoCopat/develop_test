<template>
    <svg @click="close-session-red" :height="height" :width="width" :class="[fill, bgColor ]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 128 512"><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M64 360c30.9 0 56 25.1 56 56s-25.1 56-56 56s-56-25.1-56-56s25.1-56 56-56zm0-160c30.9 0 56 25.1 56 56s-25.1 56-56 56s-56-25.1-56-56s25.1-56 56-56zM120 96c0 30.9-25.1 56-56 56S8 126.9 8 96S33.1 40 64 40s56 25.1 56 56z"/></svg>
</template>

<script>
    import { defineComponent } from 'vue';

    export default defineComponent({
        props: {
            height: {
                type: Number,
                default: 20,
            },
            width: {
                type: Number,
                default: 20,
            },
            fill: {
                type: String,
                default: 'fill-gray-800',
            },
            bgColor: {
                type: String,
                default: 'inhert',
            }
        }
    });
</script>