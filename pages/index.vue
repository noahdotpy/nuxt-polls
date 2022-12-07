<template>
    <div>
        <h1>ITS ALIVE!!</h1>
        <h2>{{ count }}</h2>
        <button @click="count++">Increment</button>
        <button @click="count--">Decrement</button>
    </div>
</template>
<script setup>
let count = ref(0)
</script>
<style>

</style>
