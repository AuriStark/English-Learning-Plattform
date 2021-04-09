<template>
  <div class="about">

    <h1>This is an about page</h1>

    <v-btn class="pink white--text">Click-Me</v-btn>

    <v-btn depressed class="info"> 
      <v-icon left class="mdi mdi-car-lifted-pickup"> </v-icon>
      <span> Let's go</span>
    </v-btn>

    <v-btn depressed class="pink white--text" color="green"> 
      <v-icon left class="mdi mdi-flashlight"> </v-icon>
      <span> Light On</span>
    </v-btn>

    <v-spacer></v-spacer>
    
    <First/>
    <v-spacer></v-spacer>

    <v-btn small class="pink white--text">Click-Me</v-btn>

    <v-btn large depressed class="info hidden-md-and-down"> 
      <v-icon left large class="mdi mdi-car-lifted-pickup"> </v-icon>
      <span> Let's go</span>
    </v-btn>

    <v-btn small dark depressed > 
      <span> Light On</span>
      <v-icon small right class="mdi mdi-flashlight"> </v-icon>
    </v-btn>

    <v-spacer></v-spacer>

    <v-btn fab x-small class="purple lighten-1 white--text hidden-xs-only"> 
      <v-icon small> mdi mdi-heart-outline </v-icon>
    </v-btn>

  </div>
</template>

<script>
import First from '../components/First.vue'

export default{
  name:'About',
  components: { First },
}
</script>

