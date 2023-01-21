<template>
  <div class="col-md-4">
    <div class="card mb-4 shadow-sm">
      <img
        class="bd-placeholder-img"
        :style="{ height: '300px', width: '100%' }"
        :src="image"
      />
      <div class="card-body">
        <div class="d-flex justify-content-between align-items-center">
          <!-- Start: view | edit button -->
          <LikeorSad />
        </div>
      </div>
    </div>
  </div>
</template>
<script setup>
import LikeorSad from "./LikeorSad.vue";
defineProps({
  image: String,
});
</script>
<style scoped></style>
