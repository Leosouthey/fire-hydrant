<script setup lang="ts">
import {ref} from 'vue';
import audio from './assets/音频.mp3'
import MutedIcon from "./components/MutedIcon.vue";
import SoundIcon from "./components/SoundIcon.vue";

const backgroundMusic = ref()
const played = ref(false)

function togglePlay() {
  if (backgroundMusic.value) {
    if (backgroundMusic.value.paused) {
      backgroundMusic.value.play();
      played.value = true
    } else {
      backgroundMusic.value.pause();
      played.value = false
    }
  }
}
</script>

<template>
  <div>
    <div id="mute" @click="togglePlay">
      <MutedIcon v-if="!played"/>
      <SoundIcon v-else/>
    </div>
    <audio ref="backgroundMusic" :src="audio" loop></audio>
    <p>
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
      失火了我第一时间用这个小火栓的水龙头怎么接都接不上去没法接我不知道当初是怎么验收通过的这个消防整栋楼上全部入住了所以导致这个火势第一时间我没法封面消防大队现在人来了他们也没法接这个水我不知道当初的时候这房子是什么验收通过怎么交的房
    </p>
  </div>
</template>

<style scoped>
p {
  user-select: none;
  position: relative;
  font-size: 15px;
  text-align: justify;
  font-weight: bold;
  font-family: sans-serif;
  width: 100vw;
  word-spacing: 0;
  letter-spacing: -1px;
  margin: 0 auto;
  color: transparent;
  background-image: url("./assets/hot.gif");
  background-size: contain;
  background-position: center;
  background-repeat: no-repeat;
  background-clip: text;
  filter: grayscale(100%) invert(100%);
  mix-blend-mode: hard-light;
}

@property --offset {
  syntax: '<length>';
  inherits: false;
  initial-value: 5px;
}

@keyframes move {
  to {
    --offset: 15px;
  }
}

#mute {
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
  color: black;
  position: fixed;
  background: white;
  opacity: 0.75;
  border-radius: 8px;
  width: 32px;
  height: 32px;
  top: 20px;
  right: 20px;
  cursor: pointer;
  z-index: 100;
  animation: move 1s infinite alternate;
}
</style>
