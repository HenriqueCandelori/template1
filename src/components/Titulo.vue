<template>
    <div class="hello">
      <h1>{{ msg }}</h1>
      
    </div>
  </template>
  
  <script>
  export default {
    name: 'TituloSimples',
    props: {
      msg: String
    }
  }

  </script>
  
  <style scoped>
h1{
    font-weight: 800;
    font-size: 38px;
    color: #fff;
    text-align: center;
}
  </style>
  