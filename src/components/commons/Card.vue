<template>
  <div class="card-song">
    <img :src="card.poster" :alt="card.title" />
    <h4>{{ card.title }}</h4>
    <p>{{ card.author }}</p>
    <p>{{ card.year }}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    card: Object,
  },
};
</script>

<style lang="scss" scoped>
.card-song {
  max-width: calc(17% - 30px);
  min-height: 400px;
  text-align: center;
  margin-top: 25px;
  background-color: #1e2d3b;
  padding: 20px;
  img {
    width: 100%;
    margin-bottom: 20px;
    cursor: pointer;
  }
  h4 {
    color: white;
    margin-bottom: 30px;
    text-transform: uppercase;
  }
  p {
    font-size: 15px;
    color: #888;
  }
}
</style>