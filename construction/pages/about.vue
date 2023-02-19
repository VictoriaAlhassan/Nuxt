<template>
    <div>
      <h1>About Us</h1>
      <p>We are a construction company that specializes in building custom homes and commercial properties.</p>
      <h2>Our Team</h2>
      <ul>
        <li v-for="member in team">{{ member.name }} - {{ member.title }}</li>
      </ul>
      <h2>Our Projects</h2>
      <ul>
        <li v-for="project in projects">{{ project.name }} - {{ project.type }}</li>
      </ul>
    </div>
  </template>
  

  <script>
export default {
  data() {
    return {
      team: [
        { name: 'John Smith', title: 'CEO' },
        { name: 'Jane Doe', title: 'Architect' },
        { name: 'Bob Johnson', title: 'Project Manager' }
      ],
      projects: [
        { name: 'Custom Home in the Hills', type: 'Residential' },
        { name: 'Office Building Downtown', type: 'Commercial' },
        { name: 'Renovation of Historic Landmark', type: 'Historical' }
      ]
    }
  }
}
</script>

<style>
h1 {
  font-size: 2rem;
  margin-bottom: 1rem;
}
h2 {
  font-size: 1.5rem;
  margin-top: 2rem;
  margin-bottom: 1rem;
}
ul {
  list-style: none;
  padding: 0;
  margin: 0;
}
li {
  margin-bottom: 0.5rem;
}
</style>



<!-- <template>
    <div>
   <h2>About</h2>
    </div>
</template>

<script setup>

</script>

<style scoped>
h2{
    margin-bottom: 20px;
    margin-top: 30px;
    font-size: 36px;
}
</style> -->