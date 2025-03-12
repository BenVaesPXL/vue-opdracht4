<script>
  export default {
    data(){
      return {
        title: "Web Advanced",
        intro: "Welkom in deze cursus",
        linkUrl: "https://vuejs.org",
        imageUrl:"https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/1200px-Vue.js_Logo_2.svg.png",
        imageheight: 100,
        imagewidth: 100
      }
    }
  }
</script>

<template>
  <h1>{{title}}</h1>
  <p>{{intro}}</p>
  <a :href="linkUrl">
    <img :src="imageUrl" alt="vue logo" :height="imageheight" :width="imagewidth" />
  </a>
</template>

<style scoped>
</style>