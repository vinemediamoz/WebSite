<template>
  <VideoBg
    :sources="['https://assets.website-files.com/558b0f96b49c4b9557cb23d5/5ce2cf198eff8bbb980e5bbb_0519-WEBLOOP-transcode.mp4']" 
    img="https://assets.website-files.com/558b0f96b49c4b9557cb23d5/5ce2cf198eff8bbb980e5bbb_0519-WEBLOOP-transcode.mp4">
    <!-- If you want to add content here, a slot is waiting! -->
    <v-layout justify-center align-center>
      <v-ripple>
<v-btn large color="primary"> Continuar a Ver</v-btn>
      <v-btn large color="warning"> Subscriver </v-btn>
      </v-ripple>
      

    </v-layout>

  </VideoBg>
</template>

<script>

import VideoBg from 'vue-videobg'

export default {
name: "Gantt",
  components: {
    VideoBg
  },
  data() {
    return {
        url:""
    };
  },
}
</script>
