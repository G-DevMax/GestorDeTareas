<template>
  <div class="home">
    <div class="container">
      <div class="text-center">
        <img alt="Vue logo" src="../assets/logo.png">
          <h1>Bienvenido al Gestor de Tareas</h1>
          <p>En esta aplicación hecha con Vue, podra gestionar sus tareas, agregando nuevas, cargando las que ya tiene o hacer las dos cosas a la vez. También podrá marcar y desmarcar para indicar 
            si una tarea esta completa o no.</p>
        </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
}
</script>

<style>
h1 {
  color: #42b983;
  text-shadow: 2px 2px 2px black;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>