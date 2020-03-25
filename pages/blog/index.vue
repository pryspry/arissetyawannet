<template>
  <div>    <h1>{{blogPost.title}}</h1>
  </div>
</template>

<script>
export default {
  computed: {
    blogPosts() {
      return this.$store.state.blogPosts;
    },
  },
};
</script>

<style>

</style>