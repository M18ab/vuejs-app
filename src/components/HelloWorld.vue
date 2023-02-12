<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div>
  <button class="dup"> Duplicate! </button>
  <button class="backg" id="backg"> Red Background! </button>
  <button class="head" id="head"> Heading! </button>
  <button class="del"> Delete! </button>

  <div class="two">
    <div class="card" id="card1">
    <h2 id="header"> W2 Homework </h2>
      <h3>By Spenser McLaughlin</h3>
       <img src="https://avatars.githubusercontent.com/u/329735?v=4" alt="btopro"/>
      <p id="paragraph"> </p>                 
      <button class="btn" id="btn"> Details </button>
    </div>
  </div>
</div>

  <p>
    Check out
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p>
    Install
    <a href="https://github.com/johnsoncodehk/volar" target="_blank">Volar</a>
    in your IDE for a better DX
  </p>
  <p class="read-the-docs">Click on the Vite and Vue logos to learn more</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
