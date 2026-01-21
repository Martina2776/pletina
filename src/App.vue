<script setup>
import bar1 from './components/bar1.vue'
import bar2 from './components/bar2.vue';
import bar3 from './components/bar3.vue';
import bar4 from './components/bar4.vue'; 
import bar5 from './components/bar5.vue';
import bar6 from './components/bar6.vue';
import bar7 from './components/bar7.vue';
import bar8 from './components/bar8.vue';
import bar9 from './components/bar9.vue';
import bar10 from './components/bar10.vue';
import cassette from './components/cassette.vue';
</script>

<template>
<body>
  <div class="app-wrapper">
    <div class="container">
      <div id="main-div">
        <bar1></bar1>
        <bar2></bar2>
        <bar3></bar3>
        <bar4></bar4>
        <bar5></bar5>
        <bar6></bar6>
        <bar7></bar7>
        <bar8></bar8>
        <bar9></bar9>
        <bar10></bar10>
      </div>
    </div>
    <div class="reproductor">
      <cassette></cassette>
    </div>
  </div>
</body>
</template>

<style scoped>
.app-wrapper {
  display: flex;
  justify-content: space-around;
  align-items: center;
  min-height: 100vh;
}

.container {
  display: flex;
  justify-content: center;
  align-items: center;
}

#main-div{
  display: flex;
}
</style>
