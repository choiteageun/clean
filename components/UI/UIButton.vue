<template>
  <button class="button">
    <slot>
    </slot>
  </button>
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
.button{
  cursor: pointer;

  min-width: 120px;
  height: 60px;
  padding-left: 30px;
  padding-right: 30px;
  background-color: white;
  color:$primary;
  border:2px solid $primary;
  outline: none;
  appearance: none;

  font-size: 1rem;
  font-weight: bold;
  border-radius: 30px;

  &:hover{
    background-color: rgba($primary, 0.1);
    border-color: darken($primary, 10%);
  }
}
</style>
