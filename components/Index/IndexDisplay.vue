<template>
  <section class="conA">
    <div class="backgroundImg">
      <div class="container intro-text center-text">
        <div class="intro-lead-in huge-text m-b-1"><span>대한민국 대표</span></div>
        <div class="intro-heading huge-text m-b-1">청결 관리 업체</div>
        <h3 class="sub-heading m-b-2">서울 및 수도권 건물 주1회 월 45000원부터</h3>
        <div class="intro-btns">
          <UIButton>등록</UIButton>
          <UIButton>신청</UIButton>
        </div>
      </div>
    </div>
    <!-- <UIButton>등록</UIButton> -->
    <div class="m-t-1">
      가나다
    </div>
  </section>
</template>
<script>
export default {
  components: {},
  data() {
    return {}
  }
}
</script>
<style lang="scss" scoped>
.backgroundImg {
  background-image: url('/img/main/main_background.jpg');
  background-repeat: no-repeat;
  background-size: cover;
  background-position: 50% 50%;
  min-height: 100vh;
  .intro-text {
    font-family: Noto Sans Korean, sans-serif;
    padding-top: 250px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    .intro-lead-in {
      animation: reveal 4s;
      span {
        text-shadow: rgba(255, 255, 255, 1) 0px 0px 4px;
      }
    }

    .intro-heading {
      position: relative;
      animation: slideDown 4s;
    }

    .sub-heading {
      animation: opacityFade 4s;
      text-shadow: rgba(255, 255, 255, 1) 0px 0px 4px;
    }
    .intro-btns {
      margin-top: 20px;
      animation: blockAni 4s;
    }

    @keyframes reveal {
      0% {
        opacity: 0;
        max-width: 400px;
      }
      10% {
        opacity: 0;
        max-width: 400px;
      }
      20% {
        opacity: 0.5;
      }
      30% {
        opacity: 1;
        max-width: 1200px;
      }
      40% {
        opacity: 1;
        max-width: 1200px;
      }
    }
    @keyframes slideDown {
      0% {
        top: -50px;
        opacity: 0;
      }
      50% {
        top: 0px;
        opacity: 0.4;
      }
      60% {
        top: 0px;
      }
      70% {
        opacity: 1;
      }
    }
    @keyframes opacityFade {
      0% {
        opacity: 0;
      }
      60% {
        opacity: 0;
      }
      90% {
        opacity: 1;
      }
    }
    @keyframes blockAni {
      0% {
        opacity: 0;
      }
      90% {
        opacity: 0;
      }
      91% {
        opacity: 1;
      }
    }
  }
}
</style>
