<template>
  <div id="app" class="row hero no-gutters">
    <ColumnaUno></ColumnaUno>
    <columnaDos></columnaDos>
  </div>
</template>

<script>
import ColumnaUno from "./components/ColumnaUno";
import ColumnaDos from "./components/ColumnaDos";

export default {
  name: 'App',
  components: {
    ColumnaUno,
    ColumnaDos
  }
}
import '../node_modules/jquery/dist/jquery.min.js';
import '../node_modules/popper.js/dist/umd/popper.js';
import '../node_modules/bootstrap/dist/js/bootstrap.min.js';
</script>

<style>
@import '../node_modules/font-awesome/css/font-awesome.css';
@import '../node_modules/bootstrap/dist/css/bootstrap.css';
@import './assets/css/estilo.css';
</style>
