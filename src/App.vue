<template>
  <v-app >
    <navbar/>
    <v-main class="grey lighten-4">
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar';
export default {
  name: 'App',
  components:{Navbar},
  data: () => ({
    //
  }),
};
</script>
