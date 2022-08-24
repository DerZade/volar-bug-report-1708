<template>
  <A />
</template>

<script lang="ts" setup>
import { defineAsyncComponent } from "vue";

const A = defineAsyncComponent(() => import("./A.vue"));
</script>
