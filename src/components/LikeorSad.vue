<template>
  <div class="btn-group">
    <button type="button" class="btn btn-sm btn-outline-success" @click="ilike">
      {{ likes }} Likes
    </button>
    <button type="button" class="btn btn-sm btn-outline-danger" @click="isad">
      {{ sads }} Sad
    </button>
  </div>
</template>
<script setup>
import { ref } from "vue";
let [likes, sads] = [ref(0), ref(0)];
function ilike() {
  return likes.value++;
}
function isad() {
  return sads.value++;
}
</script>
<style scoped></style>
