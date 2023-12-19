<template>
<!--Tasks
  
    1. Create a component called "Button" --DONE--
    2. This component will have a template  --DONE--
    3. Inside a template please include a button element, it will contain only a slot --DONE--
    4. Import your Button component in your App.vue to create an instance  --DONE--
    5. The instance will have Hello as a text
    6. The second instance will have a "Click" and logo-->

<ButtonComp>
  <template #deText>
    <p>Hello</p>
  </template>

  <template #deClick>
    <p>Click</p>
    <img src="../src/assets/logo.png" alt="logoo">
  </template>
</ButtonComp>


</template>

<script>
import ButtonComp from './components/ButtonComp.vue'


export default {
  name: 'App',
  components: {
    ButtonComp
  }
}
</script>

<style>
#app {
  font-family: cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
