<template>
  <div>
    <encabezado />
    <cuerpoContenido />
    <piePagina />
  </div>
</template>

<script>
import encabezado from "./components/encabezado"
import cuerpoContenido from "./components/cuerpoContenido"
import piePagina from "./components/piePagina"

export default {
  name: "App",
  components: {
    encabezado,
    cuerpoContenido,
    piePagina
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
