<template>
<Head></Head>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import Head from "./components/Head.vue";

export default defineComponent({
    name: "App",
    components: {
        Head,
    },
});
</script>
