<template>
  <section>
    <h1>Login</h1>
    <form>
      <div class="form-group">
        <input type="text" class="form-control" />
      </div>
      <p>
        <nuxt-link to="/">go to home</nuxt-link>
      </p>
      <button class="btn btn-primary" type="submit">Login</button>
    </form>
    <img src="~assets/svg/map-mark.svg" />
  </section>
</template>

<script>
export default {
  layout: "empty",
};
</script>

<style scoped>
form {
  width: 600px;
  margin: 0 auto;
}
</style>