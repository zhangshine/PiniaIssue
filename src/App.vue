<template>
    <div>{{ store.count }}</div>
</template>

<script setup lang="ts">
import { useCounterStore } from '@/store';

const store = useCounterStore();
</script>

<style lang="scss">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
