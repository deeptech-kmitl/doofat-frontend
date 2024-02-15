<template>
  <div>{{ $auth.user }}</div>
</template>

<script>
export default {
  name: "HomePage",
  middleware: "auth",
};
</script>

<style></style>
