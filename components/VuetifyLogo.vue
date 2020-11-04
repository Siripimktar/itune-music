<template>
  <img
    class="iTunemusicLogo"
    alt="iTunemusic Logo"
    src="https://i.imgur.com/yGF2bPO.png"
  >
</template>

<style>
.iTunemusicLogo{
  height: 35%;
  width: 35%;
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
