<template>
  <header>
    <div class="container">
      <img src="../../assets/img/spotify.png" alt="logo" />
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
header {
  height: 5vh;
  background: #1e2d3b;
  .container {
    width: 95%;
    height: 100%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    img {
      width: 50px;
    }
  }
}
</style>