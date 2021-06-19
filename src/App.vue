<template>
  <v-app>
    <v-main>
      <Jasper/>
    </v-main>
    <Footer/>
  </v-app>
</template>

<script>
import Jasper from './components/Jasper';
import Footer from './components/Footer';

export default {
  name: 'App',

  components: {
    Jasper,
    Footer,
  },

  data: () => ({
    //
  })
};
</script>
