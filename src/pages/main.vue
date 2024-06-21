<script setup>
import Header from "./../components/Header/Header.vue";
import Button from "./../components/Button/Button.vue";

function onClick() {
  console.log("click");
}

let isLoad = false;
</script>

<template>
  <Header />
  <Button v-for="i in 10" @click="onClick"> asdadsdas </Button>
  <Button v-if="isLoad"> asdadsdas </Button>
</template>
