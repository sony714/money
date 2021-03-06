<template>
  <div class="nav-wrapper">
    <div class="content">
      <Nav />
      <slot />
    </div>
  </div>
</template>
<script>
export default {
  name: "Layout",
};
</script>

<style lang="scss" scoped>
.nav-wrapper {
  border: 1px solid green;
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.content {
  overflow: auto;
  flex-grow: 1;
  border: 1px solid blue;
}
</style>