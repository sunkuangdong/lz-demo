<template>
  <div>
    <button class="g-button">按钮</button>
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
  methods: {}
};
</script>

<style scoped lang='scss'>
.g-button {
  font-size: 14px;
  height: 24px;
  padding: 0 1em;
  border-radius: 2px;
  border: 1px solid #cccccc;
  background-color: white;
  &:hover {
    border-color: cornflowerblue;
  }
  &:active {
    background-color: deepskyblue;
    color: white;
  }
  &:focus {
    outline: none;
  }
}
</style>