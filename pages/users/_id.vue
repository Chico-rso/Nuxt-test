<template>
  <section>
    <h1>user{{ $route.params.id }}</h1>
  </section>
</template>

<script>
export default {
  validate({params}){
    (params === Number) ? true : false
  }
};
</script>

<style lang="scss" scoped>
</style>