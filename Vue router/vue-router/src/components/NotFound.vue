<template>
  <div class="not-found">
    Not found
  </div>
</template>

<script>
export default {
  name: "NotFound.vue"
};
</script>

<style scoped>
.not-found {
  position: absolute;
  width: 100%;
  height: 100%;
  z-index: 2;
  display: flex;
  justify-content: center;

  align-items: center;
  background-color: black;
  color: white;
  font-size: 3rem;
}
</style>
