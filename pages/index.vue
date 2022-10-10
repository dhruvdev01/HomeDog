<template>
  <div>
    <Tutorial />
    <div class="wrapper">
      <h2 class="head">Hello <span class="head__inner-el"> World</span></h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>

<style lang="scss" scoped>
.wrapper {
  height: 100vh;
  .head {
    color: red;
    &__inner-el {
      color: skyblue;
    }
  }
}
</style>
