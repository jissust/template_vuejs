<template>
    <div class="col-lg-6 col-md-12 content">
        <Nav></Nav>
        <Home></Home>
    </div>
</template>

<script>
    import Nav from "./Nav";
    import Home from "./Home";
    export default {
        name: "ColumnaDos",
        components: {
            Home,
            Nav
        }
    }
</script>

<style scoped>

</style>