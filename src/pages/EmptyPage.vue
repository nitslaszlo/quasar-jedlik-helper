<script setup lang="ts">
import { computed, reactive } from "vue";

// import { useStore } from "src/stores/store";
// import { onMounted } from "vue";
// import { date } from "quasar";
// import router from "src/router";

// const store = useStore();

// onMounted(() => {
//   store.many_GetAll();
// });

const author = reactive({
  fname: "John",
  lname: "Doe",
  books: ["Vue 2 - Advanced Guide", "Vue 3 - Basic Guide"],
});

const fullName = computed(() => {
  return `${author.fname} ${author.lname}`;
});
</script>

<template>
  <q-page class="q-pa-xl">
    <h1>árvíztűrőtükörfúrógép</h1>
    <h1>ÁRVÍZTŰRŐTÜKÖRFÚRÓGÉP</h1>
  </q-page>
</template>

<style lang="scss" scoped></style>
