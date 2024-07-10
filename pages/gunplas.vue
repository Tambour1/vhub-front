<template>
    <div class="">
      <h1>Abouti</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      <div>
      <ul>
        <li v-for="gunpla in data" :key="gunpla.id">
          {{ gunpla.name }}
        </li>
      </ul>
    </div>
    </div>
  </template>
  
  <script setup>
    const { data, refresh, error } = await useJsonPlaceholderData('gunplas')
  </script>
  


    
  