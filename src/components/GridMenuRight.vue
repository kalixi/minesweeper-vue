<template>
  <v-container class="text-center">
    <grid-size />
    <grid-restart />
  </v-container>
</template>

<script>
import GridSize from "./GridSize";
import GridRestart from "./GridRestart";

export default {
  components: {
    GridSize,
    GridRestart
  }
};
</script>

<style lang="scss" scoped>
@media(max-width: 516px) { 
  .container {
    order: 3;
    margin: 0;
  }
}
</style>