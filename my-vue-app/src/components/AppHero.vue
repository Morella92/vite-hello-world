<template>
    <div class="bg-image">
        <h1 class="bg-green">
            {{ title }}
        </h1>
    </div>
</template>

<script>
export default {
    data() {
        return {
            
            title: 'La mia prima app con Vite!',

        }
    }
}
</script>

<style>
.bg-image {
    background-image: url(../img/images.jpg);

}

.bg-green {
    background-color: green;
    color: white;
    font-weight: 600;
}
</style>