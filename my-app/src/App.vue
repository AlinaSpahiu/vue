
<template>
<div id="app">
      <h3> Hello there! </h3>
      <!-- <Test /> -->
      <h2> {{name}}</h2>
  </div>
</template>



<script>
// import Test from './components/Test'
const data = {
  "name": "Alina Spahiu",
  "about": "Full stack Developer more focused in MERN and MEVN stacks",
  "image" : "https://media-exp1.licdn.com/dms/image/C4D03AQG3KDiMRNm3Rw/profile-displayphoto-shrink_800_800/0/1601975574996?e=1611792000&v=beta&t=5a8cM4fmp7G7Y7P4HCINfdk01B_XigTLkfP6ueTMl1g",
   "age" : 27
}
export default {
  name: 'App',
  components: {
          // Test,

  },
  data: data
}
</script>




<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}
.btn{
  display: inline-block;
  border: none;
  background: #555;
  color: #fff;
  padding: 7px 20px;
  cursor: pointer;
}
</style>
