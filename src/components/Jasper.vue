<template>
  <v-container fluid fill-height>
    <video autoplay muted loop id="background">
      <source src="../assets/welcome_jasper_540_non_audio.mp4" type="video/mp4">
    </video>

    <div id="title" class="text-center">
      <h1 class="font-weight-black">JASPER7SE</h1>
    </div>

    <div id="background2"></div>

    <v-row justify="end" align-content="center" style="height: 100%; z-index: 4;">
      <v-col xs="12" sm="6">

        <v-row justify="center" class="pa-5">
          <v-avatar
            size="256"
          >
            <img src="https://pbs.twimg.com/media/DxvbpsCU8AA0lwt?format=jpg">
          </v-avatar>
        </v-row>

        <v-row class="font-weight-black white--text pa-5" justify="center">
          <div class="text-center">
            <p>Jasper7se</p>
            <p>VALORANT EP2. ACT3 レディアント</p>
          </div>
        </v-row>

        <v-row class="text-center align-center" justify="center">
          <a class="pa-5 ma-2" href="https://www.youtube.com/channel/UCzAMU5Kgj8fGxVtcwTcq-_g" target="_blank">
            <img src="../assets/youtube.png" alt="Youtube" width="44px">
          </a>
          <a class="pa-5 ma-2" href="https://twitter.com/Jasper7se" target="_blank">
            <img src="../assets/twitter.png" alt="Twitter" width="44px">
          </a>
          <a class="pa-5 ma-2" href="https://www.twitch.tv/jasper7se" target="_blank">
            <img src="../assets/twitch.png" alt="Twitch" width="36px">
          </a>
          <a class="pa-5 ma-2" href="https://github.com/Lycheejam/anti_jasper7se" target="_blank">
            <img src="../assets/github_white.png" alt="Github" width="42px">
          </a>
        </v-row>
        
      </v-col>
    </v-row>

  </v-container>
</template>

<script>
  export default {
    name: 'Jasper',
  }
</script>

<style>
#background {
  position: absolute;
  left: 0;
  top: 0;
  object-fit: cover;
  width: 100%;
  height: 100%;
  justify-content: center;
  align-items: stretch;
  z-index: 1;
}

#title {
  position: absolute;
  left: 0;
  right: 0;
  margin: auto;
  font-size: 128px;
  z-index: 2;
  overflow: hidden;
  white-space: nowrap;
  text-overflow: clip;
}

#background2 {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(-45deg, #000000 0%, #000000 50%, #ffffff00 50%, #ffffff00 100%);
  z-index: 3;
}
</style>