<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links11</h2>
    <ul>
      <el-button type="primary">主要按钮</el-button>
      <li>
        <a
          href="https://vuejs.org"
          target="_blank"
          rel ="noopener noreferrer"
        >
          Core Docs11
        </a>
      </li>
      <li>
        <a
          href="https://forum.vuejs.org"
          target="_blank"
          rel ="noopener noreferrer"
        >
          Forum11
        </a>
      </li>
      <li>
        <a
          href="https://chat.vuejs.org"
          target="_blank"
          rel ="noopener noreferrer"
        >
          Community Chat11
        </a>
      </li>
      <li>
        <a
          href="https://twitter.com/vuejs"
          target="_blank"
          rel ="noopener noreferrer"
        >
          Twitter
        </a>
      </li>
      <br>
      <li>
        <a
          href="http://vuejs-templates.github.io/webpack/"
          target="_blank"
          rel ="noopener noreferrer"
        >
          Docs for This Template
        </a>
      </li>
    </ul>
    <h2>Ecosystem</h2>
    <ul>
      <li>
        <a
          href="http://router.vuejs.org/"
          target="_blank"
          rel ="noopener noreferrer"
        >
          vue-router
        </a>
      </li>
      <li>
        <a
          href="http://vuex.vuejs.org/"
          target="_blank"
          rel ="noopener noreferrer"
        >
          vuex
        </a>
      </li>
      <li>
        <a
          href="http://vue-loader.vuejs.org/"
          target="_blank"
          rel ="noopener noreferrer"
        >
          vue-loader
        </a>
      </li>
      <li>
        <a
          href="https://github.com/vuejs/awesome-vue"
          target="_blank"
          rel ="noopener noreferrer"
        >
          awesome-vue
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
