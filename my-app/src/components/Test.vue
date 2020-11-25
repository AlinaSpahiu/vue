<template>
  <div class="container">
    <h1> Students</h1>
      <div class="row d=flex align-items-center" v-for="person in persons" :key="person.id">
          <div class="col">
               <h3> {{person.name}} </h3>
               <h5> {{person.about}} </h5>
               <h6> {{person.age}} </h6>
          </div>

          <div class="col-sm-4 mt-3">
              <img class="img-fluid" v-bind:src="person.image" v-bind:alt="person.name">
          </div>
      </div>
  </div>
</template>



<script>

export default {
    name: "Test",
    data() {
    return {
      persons: [
        {
      id: 1,
      name: "Alina Spahiu",
      about: "Full stack Developer more focused in MERN and MEVN stacks",
      image:
        "https://media-exp1.licdn.com/dms/image/C4D03AQG3KDiMRNm3Rw/profile-displayphoto-shrink_800_800/0/1601975574996?e=1611792000&v=beta&t=5a8cM4fmp7G7Y7P4HCINfdk01B_XigTLkfP6ueTMl1g",
      age: "27 years old",
    },
    {
      id: 2,
      name: "Klevin Bazaiti",
      about: "Full stack Developer more focused in MERN stacks",
      image:
        "https://avatars0.githubusercontent.com/u/31502516?s=400&u=44bff5d57c6009866462e66fb6bed69ea045ac1e&v=4",
      age: "22 years old",
    },
    {
      id: 3,
      name: "Stefano Casasola",
      about: "React Developer",
      image:
        "https://avatars0.githubusercontent.com/u/25089405?s=400&u=e104db3205ad1f337fac2a9452367139d22c0d74&v=4",
      age: "30 years old",
    },
      ]
    }
  },
}
</script>



<style scoped>

</style>