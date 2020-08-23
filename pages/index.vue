<template>
  <div>
      <ul>
          <li><nuxt-link to="/blog/blog-post">Blog Post 1</nuxt-link></li>
          <li><nuxt-link to="/blog/blog-post">Blog Post 2</nuxt-link></li>
          <li><nuxt-link to="/blog/blog-post">Blog Post 3</nuxt-link></li>
      </ul>
  </div>
</template>

<script>
export default {
  head() {
    return {
      script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
    };
  },
};

</script>

<style>

</style>
