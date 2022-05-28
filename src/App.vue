<template>
  <div>
    <h1> Twoj e-mail to {{ email }} and password {{password}}</h1>.
    <input type="email" v-model="email">
    <input type="password" v-model="password">
  </div>
</template>

<script>

export default {

data() {
  return {
    email: '',
    password: ''
  };
}
  
}
</script>

<style>

h1{
  color:black;
  text-align: center;

}



</style>
