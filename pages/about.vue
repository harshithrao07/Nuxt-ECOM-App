<template>
    <div>
        <h1>About</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab voluptatibus facere quibusdam accusamus. Quaerat
            mollitia quam ullam temporibus rem cumque!</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab voluptatibus facere quibusdam accusamus. Quaerat
            mollitia quam ullam temporibus rem cumque!</p>
        <p>{{ data }}</p>
    </div>
</template>

<script setup>
    const { data } = await useFetch('/api/currency/INR');
</script>

<style scoped>
h1 {
    margin-top: 30px;
    font-size: 32px;
}

p {
    margin-top: 35px;
    font-size: 16px;
}</style>