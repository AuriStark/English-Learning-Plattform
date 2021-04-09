<template>
  <v-app class="grey lighten-4">
    <!-- 
      Purple 
      Purple = #800080
      Fuchsia =	#FF00FF

      or This One  PS: Check Out Purple Palette On Vuetify
      A = #461A42
      B = #623C5E
    -->
    <v-main>
      <router-link to="/">Todo</router-link> |
      <router-link to="/home">Home</router-link> |
      <router-link to="/about">About</router-link>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
  data: () => ({
    //
  }),
};
</script>
