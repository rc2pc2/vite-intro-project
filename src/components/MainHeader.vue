<script>
export default {
    name: 'MainHeader',
    data() {
        return {
            message: ''
        }
    },
    methods: {

    },
    mounted() {
        console.warn('Main header initialized!');
    },
}
</script>

<template>
    <header>
        <h2>
            Main Header
        </h2>
        <div>
            <input type="text" v-model="message">
        </div>
        <h3>
            {{ message }}
        </h3>
    </header>
</template>

<style>
</style>