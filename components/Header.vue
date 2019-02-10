<template>
  <div class="m-b-5">
    <header class="header">
      <div class="container">
        <div class="logo">
          <h3>클린</h3>
        </div>
        <div class="menu-wrapper">
          <ul class="menu-list">
            <li class="menu-item p-lr-1 bold-text">가사도우미</li>
            <li class="menu-item p-lr-1">침대가전청소</li>
            <li class="menu-item p-lr-1">이사청소</li>
          </ul>
          <ul class="menu-list">
            <li class="menu-item p-lr-1">고객센터</li>
            <li class="menu-item p-lr-1 primary-text">클리너모집</li>
          </ul>
        </div>
      </div>

    </header>
  </div>
</template>

<script>

export default {
  components:{

  },
  data(){
    return{

    }
  }
}
</script>

<style lang="scss" scoped>
.header{
  position: fixed;
  z-index: 10;
  width: 100%;
  height: 50px;
  background-color: rgba(white, 0.8);
  border-bottom: 1px solid #ccc;
  left:0;
  top:0;
  .container{
    display: flex;
    align-items: center;
    height: 100%;
    .logo{
      justify-content: center;
      display: flex;
      align-items: center;
      width: 100px;
      height:100%;
      padding-right: 20px;
    }
    .menu-wrapper{
      flex: 1;
      display: flex;
      justify-content: space-between;
      .menu-list{
        display: flex;
        .menu-item{
          height:100%;
        }
      }
    }
  }
}
</style>
