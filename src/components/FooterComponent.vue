<template>
  <footer>
    <div class="three-cols-grid">
      <div class="left">
        <p>text 1</p>
      </div>
      <div class="center">
        <p>text 2</p>
      </div>
      <div class="right">
        <p>text 3</p>
      </div>
    </div>
    <div>
      <p class="text-center">© Angel112 | 2022</p>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
};
</script>

<style lang="scss">
footer {
  background-color: #000;
  color: rgb(207, 207, 207);
  padding-bottom: 10px;
}
.three-cols-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  justify-content: space-evenly;
  justify-items: center;
  align-content: space-evenly;
  align-items: center;
  height: 90px;
}
</style>
