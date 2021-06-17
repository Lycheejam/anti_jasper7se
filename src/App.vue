<template>
  <v-app>
    <v-main>
      <Jasper/>
    </v-main>
  </v-app>
</template>

<script>
import Jasper from './components/Jasper';

export default {
  name: 'App',

  components: {
    Jasper,
  },

  data: () => ({
    //
  }),
};
</script>
