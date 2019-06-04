<template>
  <header>
    <h2>Header</h2>
<ul>
  <li>
<nuxt-link to="/about">about</nuxt-link>

  </li>
  <li>
    <nuxt-link to="/">home</nuxt-link>
    </li>  
  </ul>
    </header>
</template>
<script>
export default {
  name:"appheader"
}
</script>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover {
  background-color: #111;
}
</style>

