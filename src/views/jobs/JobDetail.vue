<template>
  <h1>Job details page</h1>
  <p>The job id is {{ id }}</p>
</template>

<script>
export default {
  // data() {
  //   return {
  //     id: this.$route.params.id,
  //   };
  // },
  props: ['id'],
};
</script>

<style></style>
