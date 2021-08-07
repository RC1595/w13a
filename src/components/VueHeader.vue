<template>
    <div>
        <h1>Welcome</h1>
        <nav>
            <a href="">Link</a>
            <a href="">Link</a>
            <a href="">Link</a>
        </nav>

    </div>
</template>

<script>
    export default {
        name : "VueHeader"
    }
</script>

<style scoped>
h1 {
    color:cyan
}
div {
    background-color: darkorchid;
    height: 20vh;
}

a {
    color:cyan;
    border:rgb(11, 175, 175) solid 2px;
    margin: 3%;
}

</style>