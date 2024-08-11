<template>
  <img alt="Vue logo" src="./assets/devvue.jpeg" class="rounded-image">
  <HelloWorld msg="Hugo Silva"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
  background-color:  ; /* COR DO FUNDO IMAGEM */
}
.rounded-image {
  border-radius: 50%; /* Torna a imagem arredondada */
  border: 5px solid purple; 
  width: 400px; /* largura da imagem */
  height: 400px; /* altura da imagem */
  object-fit: cover; /* Mantém a qualidade da imagem */
}
</style>
