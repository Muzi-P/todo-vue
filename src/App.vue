<template>
  <v-app>
      <!-- <Login/> -->
      <Signup/>
  </v-app>
</template>

<script>
// import Login from './components/Auth/Login';
import Signup from './components/Auth/Signup';

export default {
  name: 'App',
  components: {
    Signup
  }
};
</script>
