<template>
  <div class="wrapper" role="main">
    <nuxt />
  </div>
</template>

<script>

export default {
  components: {
  },
};
</script>


<style lang="scss" scoped>
.wrapper {
  margin: 3rem;
  background: #f7f7f7;
}

@media screen and (max-width: 1024px) {
  .wrapper {
    margin: 0;
  }
}
</style>
