<template>
    <div class="blog-post">
      <h1>{{ title }}</h1>
      <p>{{ content }}</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BlogPost',
    props: {
      title: String,
      content: String
    }
  }
  </script>
  
  <style scoped>
  .blog-post {
    margin: 20px;
  }
  </style>
  