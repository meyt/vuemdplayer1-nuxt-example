<template>
  <div class="container">
    <audio-player src="/audio.mp3" />
    <video-player src="/video.mp4" />
  </div>
</template>

<script>
import { audioPlayer, videoPlayer } from 'vue-md-player'
import 'vue-md-player/dist/vue-md-player.css'
export default {
  components: {
    audioPlayer,
    videoPlayer
  }
}
</script>

<style>
  .container {
    max-width: 600px;
    margin: auto;
  }
  .vuemdplayer {
    margin-bottom: 16px;
  }
</style>
