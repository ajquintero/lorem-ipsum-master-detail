<template>
  <li>
      <p class="name boxes"> {{ ipsum.title }}</p>
      <p class="boxes">Category: {{ ipsum.category }}</p>
  </li>
</template>

<script>
export default {
  props: {
    ipsum: Object
  }

};
</script>

<style>
li {
    position: relative;
    height: 150px;
    border: 5px solid;
    background: #57D584;
    border: 3px solid navy;
    padding: 10px;
    margin-bottom: 10px;
    box-shadow: 2px 2px 2px white;
  }
  .boxes{
    color: black;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    text-align: center;
  }
  .name {
    font-size: 1.5em;
  }
</style>
