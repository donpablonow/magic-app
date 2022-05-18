<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})

const count = ref(0)
</script>

<template>
<div id="wrap">
  <div class="card"  @mouseleave="count++">
    <h1>{{ msg }}</h1>
    <button type="button" >count is: {{ count }}</button>
  </div>
</div>
</template>

<style scoped>
button {
    display:block;
    position:absolute;
    bottom:20px;
    margin:0 auto;
  cursor: pointer;
  border:none;
  background:#fff;
  color:#212534;
  padding:10px;
}

h1 {
    display:none;
    z-index:4;
}


.card {
  background: #191c29;
  width: var(--card-width);
  height: var(--card-height);
  left:  calc(var(--card-width) / .5);
  top: calc(var(--card-height) / 4);
  padding: 3px;
  position: fixed;
  border-radius: 6px;
  justify-content: center;
  align-items: center;
  text-align: center;
  display: flex;
  font-size: 1.5em;
  z-index:1;
}

.card:hover:before, .card:hover:after {
  transition: color 1s;
  opacity: 1;
}

.card:hover h1{
    display:block;
}

.card:hover button{
    display:none;
}


.card::before {
    opacity: 0;
  content: "";
  width: 104%;
  height: 102%;
  z-index:2;
  border-radius: 8px;
  background-image: linear-gradient(
    var(--rotate)
    , #5ddcff, #3c67e3 43%, #4e00c2);
    position: absolute;
    top: -1%;
    left: -2%;
    animation: spin 2.5s linear infinite;
}

.card::after {
    z-index:3;
    opacity: 0;
  position: absolute;
  content: "";
  top: calc(var(--card-height) / 6);
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  margin: 0 auto;
  transform: scale(0.8);
  filter: blur(calc(var(--card-height) / 6));
  background-image: linear-gradient(
    var(--rotate)
    , #5ddcff, #3c67e3 43%, #4e00c2);
  transition: opacity .5s;
  animation: spin 2.5s linear infinite;
}

@keyframes spin {
  0% {
    --rotate: 0deg;
  }
  100% {
    --rotate: 360deg;
  }
}

a {
  text-decoration: none;
  font-weight: bold;
  margin-top: 2rem;
}
</style>
