<template>
    <div>
        <h1>Welcome</h1>
        <NavBar></NavBar>
    </div>
</template>

<script>
    import NavBar from './NavBar.vue'
    export default {
        name : "VueHeader",
        components : {
            NavBar
        } 
    }
</script>

<style scoped>
h1 {
    color:mediumblue;
}
div {
    border-bottom: mediumblue 2px solid;
    background-color:lavender;
    height: 20vh;
}
</style>