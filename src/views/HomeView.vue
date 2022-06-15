<script setup></script>

<template>
  <header>
    <img src="" alt="Logo" />
    <h1>titulo</h1>
    <div>
      <a href="">Cadastro</a>
      <a href="">Login</a>
    </div>
  </header>
  <main>Main</main>
  <footer>Footer</footer>
</template>

<style>
* {
  margin: 0px;
  padding: 0px;
}

header {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;

  height: 10vh;
  background-color: gray;
}

main {
  height: 90vh;
  background-color: lightblue;
}
footer {
  background-color: gray;
  height: 10vh;
}
</style>
