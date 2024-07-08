<template>
    <div id="app">
      <BlogPost title="My First Blog Post" content="This is the content of my first blog post." />
      <BlogPost title="My Second Blog Post" content="This is the content of my second blog post." />
    </div>
  </template>
  
  <script>
  import BlogPost from './components/BlogPost.vue'
  
  export default {
    name: 'App',
    components: {
      BlogPost
    }
  }
  </script>
  
  <style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
  </style>
  