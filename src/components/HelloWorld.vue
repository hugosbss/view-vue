<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    
    <ul>
      <li>
        <a href="mailto:ohugodev@outlook.com" target="_blank" rel="noopener">           
          <font-awesome-icon :icon="['fas', 'envelope']" style="color: orange; font-size: 32px;" />
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/hugo-wg-silva23?" target="_blank" rel="noopener">
          <font-awesome-icon :icon="['fab', 'linkedin']" style="color: #0077b5; font-size: 32px;" />
        </a>
      </li>
      <li>
        <a href="https://github.com/hugosbss?tab=repositories" target="_blank" rel="noopener">
          <font-awesome-icon :icon="['fab', 'github']" style="color: black; font-size: 32px;" /> 
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
  text-decoration: none;
  display: flex;
  align-items: center;
}
font-awesome-icon {
  margin-right: 8px;
}
</style>
