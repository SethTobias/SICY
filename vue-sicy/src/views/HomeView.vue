<template>
  <div class="home">
  <div class="landing">
    <h1 class="main">
      Selector I Choose You!
    </h1>
  </div>
  <div class="content">
    <div class="display">
      <div class="syntax">
        <h2 class="sub">Basic Syntax</h2>
        <p class="selector">element &lbrace;</p>
        <p class="selector">property: value;</p>
        <p class="selector"> &rbrace;</p>
      </div>
      <div class="visualizer"></div>
      <div class="explanation">
        <h3>What is a selector?</h3>
        <p>Explanation?</p>
      </div>
    </div>
  </div>
  </div>
</template>

<script>

export default {
  name: 'HomeView'
}
</script>

<style scoped>
div[class='landing'] {
  width: 100%;
  height: 100vh;
  display: flex;
  place-content: center;
  place-items: center;
  background-color: gray;
}

h1[class='main'] {
  width: fit-content;
  height: fit-content;

}

div[class='content'] {
  width: 100%;
}

div[class='display'] {
  display: flex;
  place-content: center space-evenly;
  flex-flow: row wrap;
}

div[class='syntax'] {
  width: 300px;  
  height: 300px;
  text-align: start;
  display: flex;
  place-content: center;
  place-items: center;
  flex-flow: column wrap;
}

div[class='visualizer'] {
  width: 300px;  
  height: 300px;
  background-color: blueviolet;
}

h2[class='sub'] {
  
}

p[class='selector'] {
  width: 200px;  
  line-height: 0;
}

div[class='explanation'] {
  width: 100%;  
  height: 300px;
  text-align: center;
}

</style>