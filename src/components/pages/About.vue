<template>
  <div class="about">
    <h1>This is About page</h1>
    <h2>Subtitle for about page</h2>
    <p> {{ content }}</p>
  </div>
</template>

<script>
export default {
  name: 'about',
  data () {
    return {
      content: 'About page dummy content...'
    }
  }
}
</script>
