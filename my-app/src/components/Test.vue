<template>
   <div>
      <h2> {{this.data.name}}</h2>
   </div>
</template>



<script>

const data = {
  "name": "Alina Spahiu",
  "about": "Full stack Developer more focused in MERN and MEVN stacks",
  "image" : "https://media-exp1.licdn.com/dms/image/C4D03AQG3KDiMRNm3Rw/profile-displayphoto-shrink_800_800/0/1601975574996?e=1611792000&v=beta&t=5a8cM4fmp7G7Y7P4HCINfdk01B_XigTLkfP6ueTMl1g",
   "age" : 27
}
export default {
    name: "Test",
    data(){
      return data
    }
}
</script>



<style scoped>

</style>