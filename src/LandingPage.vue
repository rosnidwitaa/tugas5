<template>
    <div id="app">
      <LandingPage />
    </div>
  </template>
  
  <script>
  import LandingPage from './components/LandingPage.vue';
  
  export default {
    name: 'App',
    components: {
      LandingPage
    }
  };
  </script>
  
  <style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
  
  body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
  }
  
  #app {
    text-align: center;
  }
  </style>
  