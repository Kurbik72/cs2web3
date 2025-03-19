<script setup>
import Hello_page from "./components/Hello_page.vue";
import Button from "./components/Button.vue";
</script>

<template>
  <div>
    <Hello_page />
    <Button />
    <div class="team">
      <p>А ЭТО НАШИ СЛОНЫ</p>
      <img src="../public/slon.jpg" alt="" />
    </div>
  </div>
</template>

<style>
@font-face {
  font-family: "TYAK";
  src: url("../assets/Sashaoluu_Uzana.otf");
}
body {
  background: url("./basketball-cs2.png");
  background-repeat: no-repeat;

  background-position: center top -100px;
}
.team p {
  display: flex;
  justify-self: center;
  align-items: center;
  padding-top: 2em;
  font-family: TYAK;
  color: rgb(255, 255, 255);
  font-weight: 800;
  font-size: 2rem;
}
.team img {
  width: 100%;
  height: 100%;
}
</style>
