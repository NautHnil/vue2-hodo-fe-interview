<template>
  <h1 class="text-center text-3xl">{{ msg }}</h1>
</template>

<script>
export default {
  name: 'HelloWord',
  props: {
    msg: String,
  },
  data() {
    return {};
  },
};
</script>
