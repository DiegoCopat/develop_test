<template>
    <svg @click="close-session-red" :height="height" :width="width" :class="[fill, bgColor ]" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512"><!--! Font Awesome Pro 6.2.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. --><path d="M512 256C512 114.6 397.4 0 256 0S0 114.6 0 256S114.6 512 256 512s256-114.6 256-256zM271 135c9.4-9.4 24.6-9.4 33.9 0s9.4 24.6 0 33.9l-87 87 87 87c9.4 9.4 9.4 24.6 0 33.9s-24.6 9.4-33.9 0L167 273c-9.4-9.4-9.4-24.6 0-33.9L271 135z"/></svg>
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
                default: 'inherit',
            },
            bgColor: {
                type: String,
                default: 'inherit',
            }
        }
    });
</script>