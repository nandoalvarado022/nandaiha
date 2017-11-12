<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <Estudios/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Estudios from './components/Estudios'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Estudios
  }
}
</script>