<template>
  <main>
    <Cards />
  </main>
</template>

<script>
import Cards from "../sections/Cards.vue";
export default {
  name: "Main",
  components: {
    Cards,
  },
};
</script>

<style lang="scss" scoped>
main {
  min-height: 95vh;
  display: flex;
  align-items: center;
}
</style>