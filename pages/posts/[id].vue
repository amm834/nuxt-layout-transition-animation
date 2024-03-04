<script setup lang="ts">
import {useRoute} from "#app";

const route = useRoute();

</script>

<template>
    Hello Post {{ route.params.id}}
</template>

<style scoped>

</style>
