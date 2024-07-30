<template>
  <div>
    <h1>Deret Bilangan Ganjil</h1>
    <h4>{{ bilangan }}</h4>
    <button v-on:click="next" >Next</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      bilangan: 1,
    };
    },
  methods: {
      next() {
          this.bilangan += 6;
    }
  },
};
</script>

<style></style>
