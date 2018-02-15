<template>
  <div class="brochure">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
        >
          Core Docs
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Brochure',
  data() {
    return {
      msg: 'Welcome to Your P2-Web App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
