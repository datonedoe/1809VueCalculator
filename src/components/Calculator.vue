<template>
  <div class="calculator">
      <div class="display">0.00000</div>
      <div>C</div>
      <div>+/-</div>
      <div>%</div>
      <div>/</div>
      <div>7</div>
      <div>8</div>
      <div>9</div>
      <div>4</div>
      <div>5</div>
      <div>6</div>
      <div>1</div>
      <div>2</div>
      <div>3</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.calculator {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-auto-rows: minmax(50px, auto);
}
</style>
