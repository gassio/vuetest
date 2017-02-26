<template>
    <div class="mod-modal">
        <p class="control has-icon">
          <input class="input" type="email" placeholder="Email">
          <span class="icon is-small">
      <i class="fa fa-envelope"></i>
    </span>
        </p>
        <p class="control has-icon">
          <input class="input" type="password" placeholder="Password">
          <span class="icon is-small">
      <i class="fa fa-lock"></i>
    </span>
        </p>
        <p class="control">
          <button class="button is-success">
            Login
          </button>
        </p>
  </div>
</template>

<script>
  export default {
    name: 'modal',
    data () {
      return {

      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->


<style scoped>
</style>
