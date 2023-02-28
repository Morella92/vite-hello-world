<template>
    <div class="title-style">
        {{ title }}
    </div>
</template>

<script>
export default {
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}
</script>

<style>
.title-style {
    background-color: green;
    color: white;
    font-weight: 600;
    font-size: 40px;
}
</style>