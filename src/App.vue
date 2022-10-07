<template>
  <v-app>
   <!-- <navbar-comp /> -->
   <form-comp/>
  </v-app>
</template>

<script>
import FormComp from './components/FormComp.vue';
// import NavbarComp from './components/NavbarComp.vue';

export default {
  name: 'App',

  components: {
    // NavbarComp,
    FormComp
  },

  data: () => ({
    //
  }),
};
</script>
