<script setup></script>

<template>
  <div class="button">
    <a href="https://www.faceit.com/ru/matchmaking"
      ><button>ТЫКАЙ НА ЭТУ ИМБУ БРАТАН</button></a
    >
  </div>
</template>

<style scoped>
@font-face {
  font-family: "TYAK";
  src: url("../assets/Sashaoluu_Uzana.otf");
}
.button button {
  background-color: rgb(255, 3, 3);
  border-radius: 10px;
  width: 200px;
  height: 60px;
  font-family: TYAK;
  font-size: 1.5em;
  color: rgb(255, 255, 255);
  border: none;
  font-weight: 800;
}
.button {
  display: flex;
  justify-content: center;
  align-items: center;
}
.button button {
  cursor: pointer;
}
.button button:hover {
  transform: scale(1.1);
  transition: 0.5s ease-in-out;

  background-color: rgb(176, 3, 3);
}
</style>
