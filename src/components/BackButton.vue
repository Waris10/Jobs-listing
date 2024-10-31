<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <section>
    <div class="container m-auto py-6 px-6">
      <RouterLink
        to="/jobs"
        class="text-green-500 hover:text-green-600 flex items-center"
      >
        <i class="pi pi-arrow-circle-left"></i>
        <span class="ml-2"> Back to Job Listings</span>
      </RouterLink>
    </div>
  </section>
</template>
