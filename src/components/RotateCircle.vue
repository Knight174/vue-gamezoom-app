<template>
  <div class="loader-wrap">
    <div class="loader-circles">
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
      <div class="circle"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "RotateCircle",
};
</script>

<style lang="scss" scoped>
.loader-wrap {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: 200;
  margin: auto;
  background-color: $c-black;
  overflow: hidden;
}

.loader-circles {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  margin: auto;
  transform: rotate(45deg);
  width: 200px;
  height: 200px;
}
.loader-circles .circle {
  box-sizing: border-box;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
  margin: auto;
  background-color: transparent;
  border: 4px solid #ffffff;
  border-radius: 50%;
  border-bottom-color: transparent;
  border-right-color: transparent;
  text-align: center;
}
.loader-circles .circle:nth-child(even) {
  border-color: $c-like;
  border-bottom-color: transparent;
  border-right-color: transparent;
}
.loader-circles .circle:nth-child(odd) {
  border-color: #6257bd;
  border-bottom-color: transparent;
  border-right-color: transparent;
}
.loader-circles .circle:nth-child(1) {
  width: 20px;
  height: 20px;
  animation: rotate-circle linear infinite;
  animation-duration: 12s;
}
.loader-circles .circle:nth-child(2) {
  width: 40px;
  height: 40px;
  animation: rotate-circle linear infinite;
  animation-duration: 6s;
}
.loader-circles .circle:nth-child(3) {
  width: 60px;
  height: 60px;
  animation: rotate-circle linear infinite;
  animation-duration: 4s;
}
.loader-circles .circle:nth-child(4) {
  width: 80px;
  height: 80px;
  animation: rotate-circle linear infinite;
  animation-duration: 3s;
}
.loader-circles .circle:nth-child(5) {
  width: 100px;
  height: 100px;
  animation: rotate-circle linear infinite;
  animation-duration: 2.4s;
}
.loader-circles .circle:nth-child(6) {
  width: 120px;
  height: 120px;
  animation: rotate-circle linear infinite;
  animation-duration: 2s;
}
.loader-circles .circle:nth-child(7) {
  width: 140px;
  height: 140px;
  animation: rotate-circle linear infinite;
  animation-duration: 1.7142857143s;
}
.loader-circles .circle:nth-child(8) {
  width: 160px;
  height: 160px;
  animation: rotate-circle linear infinite;
  animation-duration: 1.5s;
}
.loader-circles .circle:nth-child(9) {
  width: 180px;
  height: 180px;
  animation: rotate-circle linear infinite;
  animation-duration: 1.3333333333s;
}
.loader-circles .circle:nth-child(10) {
  width: 200px;
  height: 200px;
  animation: rotate-circle linear infinite;
  animation-duration: 1.2s;
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
@keyframes rotate-circle {
  100% {
    transform: rotate(360deg);
  }
}
</style>
