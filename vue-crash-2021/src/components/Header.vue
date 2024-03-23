<template>
    <header>
        <h1>{{  title }}</h1>
        <Button text="Add Task" color="green"/>

    </header>
</template>

<script>
    import Button from './Button'

    export default {
        name: 'Header',
        props: {
            title: String,
        },
        components: {
            Button
        }
    }
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-bottom: 20px;
    }
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400&display=swap');
</style>