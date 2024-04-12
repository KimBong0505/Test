<template>
  <!-- <div>
    <button class="btn1">ボタン1</button>
  </div> -->
  <div>
    <button class="btn1"><slot /></button>
  </div>
</template>

<style lang="scss" scoped>
.btn1 {
  width: 150px;
  height: 40px;
  line-height: 40px;
  background-color: #00a656;
  color: #ffffff;
  font-weight: bold;
  border-radius: 15px;
  border: none;
  margin: 30px;
}
</style>
