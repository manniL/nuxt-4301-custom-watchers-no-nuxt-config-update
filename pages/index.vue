<template>
  <div>{{ name }}</div>
</template>

<script>
export default {
  asyncData() {
    return {
      name: process.env.SECRET
    };
  }
};
</script>
