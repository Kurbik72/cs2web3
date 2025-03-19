<script setup lang="ts"></script>

<template>
  <div class="tyak">
    <h1>Привет братан!</h1>
    <p>Это <span> ТЯК ТИМ </span> и мы приглашаем тебя к нам в лобби</p>
  </div>
</template>

<style scoped>
@font-face {
  font-family: "TYAK";
  src: url("../assets/Sashaoluu_Uzana.otf");
}
.tyak {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  font-family: TYAK;
}
.tyak h1 {
  color: rgb(162, 65, 0);
  font-size: 4em;
  text-align: center;
  font-weight: 800;
}
.tyak p {
  color: rgb(251, 251, 251);
  font-size: 3em;
}
.tyak span {
  color: brown;
}
</style>
