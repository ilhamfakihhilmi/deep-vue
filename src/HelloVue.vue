<template>
  <div>
    <h1>Hello world</h1>
    <h4>Project vue pertama saya</h4>
    <h4>nama saya: {{ nama }}</h4>
    <h4>umur saya: {{ umur }} tahun</h4>
  </div>
</template>

<script>
export default {
  data() {
    return {
      nama: "fakih hilmi",
      umur: 25,
    };
  },    
  mounted() {
    this.umur = this.umur + 3;
  },
};
</script>

<style></style>
