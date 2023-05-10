<template>
        <a href="#"><button class="bt">{{ msg }}</button></a>      
  </template>
  
  <script>
  export default {
    name: 'BotaoHelp',
    props: {
      msg: String
    }
  }
  </script>
  
  <style scoped>
.bt{
  box-shadow: 0 0 0 1px #fff;
  background: #50B2EA; 
  border-radius: 6px; 
  padding: 15px; 
  cursor: pointer; 
  color: #fff; 
  border: none; 
  font-size: 16px; 
  height: 61px; 
  width: 192px;
}
  </style>
  