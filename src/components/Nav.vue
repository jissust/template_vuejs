<template>
    <nav class="navbar navbar-expand-lg navbar-light py-3">
        <a class="navbar-brand font-weight-bold"
           href="#">
            Webook
        </a>
        <button class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarNav"
                aria-controls="navbarNav"
                aria-expanded="false"
                aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse"
             id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item mr-3">
                    <a class="nav-link" href="#">Page 1</a>
                </li>
                <li class="nav-item mr-3">
                    <a class="nav-link" href="#">Page 2</a>
                </li>
                <li class="nav-item mr-3">
                    <a class="nav-link" href="#">Page 3</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
        name: "Nav"
    }
</script>

<style scoped>

</style>