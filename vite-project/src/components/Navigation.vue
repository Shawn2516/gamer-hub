<template>
    <div class="nav">
      <ul>
        <li>Home</li>
        <li>Blog</li>
        <li>Other Feature</li>
      </ul>
    </div>
  </template>


<style scoped>
.nav {
    background-color: black;
    height: 50px;
    width: 100%;

}

ul {
    display: flex;
    justify-content: center;
    list-style-type: none;

}

li {
    color: orange;
    padding: 5px;
    margin: 5px;  
    font-weight: bold;
}

</style>