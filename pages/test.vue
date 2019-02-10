<template>
  <div class="div">
    <div class="div one">Escape</div>
    <div class="div two">
      <span>가나다라마바사아자차카타파하</span>
    </div>
  </div>
</template>
<script>
export default {
  components: {},
  data() {
    return {}
  }
}
</script>
<style>
.div {
  font-size: 30px;
  display: inline-block;
  overflow: hidden;
  white-space: nowrap;
}

.one {
  animation: showup 7s;
}

.two {
  width: 500px;
  animation: reveal 7s;
}

.two span {
  margin-left: 0px;
  animation: slidein 7s;
}

@keyframes showup {
  0% {
    opacity: 0;
  }
  40% {
    opacity: 1;
  }
  80% {
    opacity: 1;
  }
  100% {
    opacity: 1;
  }
}

@keyframes slidein {
  0% {
    margin-left: -800px;
  }
  20% {
    margin-left: -800px;
  }
  35% {
    margin-left: 0px;
  }
  100% {
    margin-left: 0px;
  }
}

@keyframes reveal {
  0% {
    opacity: 0;
    width: 0px;
  }
  20% {
    opacity: 1;
    width: 0px;
  }
  30% {
    width: 500px;
  }
  80% {
    opacity: 1;
  }
  100% {
    opacity: 1;
    width: 500px;
  }
}
</style>
