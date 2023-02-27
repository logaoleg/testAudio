<template>
  <div id="app">
    <WebAudioRecorder />
    <!-- <Mp3AudioRecorder /> -->
    <!-- <Recorder />  -->
  </div>
</template>

<script>
import WebAudioRecorder from "./components/media-recorder/WebAudioRecorder";
// import Mp3AudioRecorder from "./components/mp3-recorder/Mp3AudioRecorder";
// import Recorder from "./components/media-recorder/Recorder";
export default {
  name: "App",
  components: {
    WebAudioRecorder,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
button + button {
  margin: 5px;
}
h1,
h2,
h3,
h4,
h5 {
  margin: 0;
}
.tools {
  margin: 10px 0px;
}
.audio-recorder {
  margin: 20px 10px;
  border: 1px solid blue;
  padding: 10px;
  text-align: left;
}
.audio {
  display: flex;
  align-items: center;
}
.audio h5 {
  order: 2;
  padding: 10px;
}
.audio audio {
  order: 1;
}
</style>
