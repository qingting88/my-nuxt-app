<template>
  <h1>Hi,{{ data?.message }}</h1>
</template>
<script setup lang="ts">
const {data} = useFetch("/api/hello");
</script>
