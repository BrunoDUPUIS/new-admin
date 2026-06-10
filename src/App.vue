<script setup>
import content from '../content/home.json'
</script>

<template>
  <h1>{{ content.titre }}</h1>
  <div>
    <p>
      {{ content.paragraph }}
    </p>
  </div>
</template>

<style scoped>
h1 {
  color: blueviolet;
  text-align: center;
}

p {
  text-align: center;
}

div {
  margin: 0 auto;
  border: 2px red solid;
  width: 500px;
}
</style>
