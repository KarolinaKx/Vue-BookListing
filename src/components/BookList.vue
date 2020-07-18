<template>

  <div>
    <h1>{{ msg }}</h1>
  </div>

</template>

<script>
  export default {
  name: 'BookList',
  data() {
    return {
      msg: 'All Books',
    };
  },
};
</script>

<style>
  h1, h2 {
  font-weight: normal;
  }
</style>
