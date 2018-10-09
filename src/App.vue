<template lang="pug">

  #app.global-wrap

    main
      app-main

</template>

<script>

  import appMain from './components/main'

  export default {
    name: 'App',
    components: {
      'app-main': appMain
    },
    data() {},
    created() {},
    mounted() {},
    methods: {}
  }

</script>

<style lang="scss">
  *{
    box-sizing: border-box;
    font-size: 100%;
    outline: none;
    text-decoration: none;
    color: #000;
    margin: 0;
    padding: 0;
    list-style: none;

  }
  a, input, button{
    transition: .3s;
  }

  ::-webkit-input-placeholder {color:#ccc;}
  ::-moz-placeholder          {color:#ccc;}/* Firefox 19+ */
  :-moz-placeholder           {color:#ccc;}/* Firefox 18- */
  :-ms-input-placeholder      {color:#ccc;}

  body{
    background: #f1f1f1;
    margin: 0;
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    font-size: 14px;

  }
</style>
