<template>
  <div>
    <h1>{{ msg }}</h1>

    <p>
      <a href="https://vitejs.dev/guide/features.html" target="_blank">
        Vite Documentation
      </a>
      |
      <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
    </p>

    <button type="button" @click="state.count++">
      count is: {{ state.count }}
    </button>
    <p>
      Edit
      <code>components/HelloWorld.vue</code> to test hot module replacement.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',

  props: {
    msg: String,
  },

  data() {
    return {
      state: {
        count: 0,
      },
    }
  }
}
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
