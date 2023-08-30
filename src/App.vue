<template>
<signUpFrom/>
</template>

<script>
import signUpFrom from './components/signUpForm.vue'

export default {
  name: 'App',
  components: {
    signUpFrom
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
  margin-top: 60px;
}
body{
  margin: 0;
  background: #eee;

}
</style>
