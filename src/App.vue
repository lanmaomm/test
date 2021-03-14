<template>
  <div class="play"></div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style scoped>
.play {
  display: inline-block;
  width: 11px;
  height: 14px;
  background-size: 100%;
  background-position: center;
  background-repeat: no-repeat;
  animation: playing 0.9s linear infinite;
  transition-delay: 300ms;
}
@keyframes playing {
  0% {
    background-image: url('https://sf3-ttcdn-tos.pstatp.com/img/edux-data/160879095347490c166341e~0x0.png');
  }
  32% {
    background-image: url('https://sf3-ttcdn-tos.pstatp.com/img/edux-data/160879095347490c166341e~0x0.png');
  }
  33% {
    background-image: url('https://sf3-ttcdn-tos.pstatp.com/img/edux-data/1608790978371accc6073ef~0x0.png');
  }
  66% {
    background-image: url('https://sf3-ttcdn-tos.pstatp.com/img/edux-data/1608790978371accc6073ef~0x0.png');
  }
  67% {
    background-image: url('https://sf6-ttcdn-tos.pstatp.com/img/edux-data/160879100063357a8579e65~0x0.png');
  }
  99% {
    background-image: url('https://sf6-ttcdn-tos.pstatp.com/img/edux-data/160879100063357a8579e65~0x0.png');
  }
  100% {
    background-image: url('https://sf3-ttcdn-tos.pstatp.com/img/edux-data/160879095347490c166341e~0x0.png');
  }
}
</style>
