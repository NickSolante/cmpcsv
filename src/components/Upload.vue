<template>
  <div>
    <!-- Plain mode -->
    <b-form-file
      v-model="file"
      :state="Boolean(file)"
      placeholder="Choose a file or drop it here..."
      drop-placeholder="Drop file here..."
    ></b-form-file>
    <div class="mt-3">Selected file: {{ file ? file.name : '' }}</div>
  </div>
</template>

<script>
import Papa from "papaparse";
export default {
  data() {
    return {
      file: null
    };
  }
};
</script>

<style scoped>
</style>