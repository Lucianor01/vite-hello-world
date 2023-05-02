<!--! SCRIPT -->
<script>

export default {
    name: "AppHero",
    data() {
        return {

        }
    },
    methods: {

    },
};

</script>

<!--! TEMPLATE -->
<template>
    <div class="container_app_hero">
        <img src="https://picsum.photos/id/237/300/300" alt="img_1">
        <h2>Immagine 1</h2>
    </div>
</template>

<!--! STYLE -->
<style scoped>
.container_app_hero {
    position: relative;
    display: block;
}

h2 {
    margin: 0;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>