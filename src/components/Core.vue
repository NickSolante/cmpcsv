<template>

<b-container class="bv-example-row">
  <b-row>
    <b-col>1 of 3</b-col>
    <b-col> <Upload></Upload></b-col>
    <b-col>3 of 3</b-col>
  </b-row>
</b-container>
 
</template>
<script>
import Upload from "./Upload";
export default {
  components: {
    Upload
  }
};
</script>
<style scoped>
</style>