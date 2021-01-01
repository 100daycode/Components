<template>
    <div class="logos-wrapper">
        <h2 class="title">Find Best Logos</h2>
        <div class="item-logos">
            <img class="logos" src="../assets/logo.png" alt="logo">
        </div>
        <div class="item-logos">
            <img class="logos" src="../assets/logo.png" alt="logo">
        </div>
        <div class="item-logos">
            <img class="logos" src="../assets/logo.png" alt="logo">
        </div>
        <div class="item-logos">
            <img class="logos" src="../assets/logo.png" alt="logo">
        </div>
    </div>
</template>

<script>
export default {
    name : 'Logos',
}

</script>

<style scoped>
.title {
    text-align: left;
    margin-bottom: 10px;
}

.logos-wrapper{
    width : 60%;
    overflow :hidden;
    margin : auto;
}

.item-logos{
    float: left;
    margin-right: 50px;
    margin-bottom: 50px;
    width: 150px;
    height: 150px;
}

.item-logos .logos {
    width: 150px;
    height: 150px;
}
</style>