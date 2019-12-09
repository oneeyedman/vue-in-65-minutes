<template>
  <div class="about">
    <h1>Hello {{their_name}}, this an about page</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>

