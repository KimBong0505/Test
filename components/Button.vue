<template>
  <div>
    <button :style="{ backgroundColor: backColor, color: color }" class="btn">
      <slot></slot>
    </button>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  backColor: {
    type: String,
    default: "#ccc",
  },
  color: {
    type: String,
    default: "#fff",
  },
});
</script>

<style scoped lang="scss">
.btn {
  width: 150px;
  height: 40px;
  line-height: 40px;
  font-weight: bold;
  border-radius: 15px;
  border: none;
  margin: 30px;
}
</style>
