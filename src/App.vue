<template>
  <div id="app">
    <exam-header></exam-header>
    <demo1/>
    <demo2/>
    <demo3/>
    <demo4/>
  </div>
</template>

<script>
import demo1 from './pages/demo1.vue';
import demo2 from './pages/demo2.vue';
import demo3 from './pages/demo3.vue';
import demo4 from './pages/demo4.vue';

export default {
  name: 'app',
  components:{
    demo1,
    demo2,
    demo3,
    demo4
  },
  data () {
    return {
    }
  }
}
</script>

<style>
#app {
  font-family: Helvetica Neue,Helvetica,PingFang SC,Hiragino Sans GB,Microsoft YaHei,SimSun,sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  padding: 20px 20%;
}

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
pre {
    padding: 16px;
    overflow: auto;
    font-size: 85%;
    line-height: 1.45;
    background-color: #f6f8fa;
    border-radius: 3px;
}
</style>
