<script setup>
import { reactive } from 'vue';
import { ref } from 'vue';
const props = defineProps(['countView']);

//ref su dung 1 object va 1 thuoc tinh
//truy cap ref bang .value
//reactive 1 object trong do co nhieu doi tuong
//reactive khong can .value
// const count = ref(1);
// const countSub = ref(1)

// const countReactive = reactive({
//   title: 'VueJS',
//   author: 'Longg'
// });

// const increase = () => {
//   count.value++;
// };

// const submitForm = (e) => {
//   e.preventDefault;
//   countSub.value++;
// };

</script>

<template>
  <div>Count:{{ props.countView }}</div>
  <button>Increase</button>
  <!-- <div class="red">This is {{ count }}</div>
  <div>Growth {{ countSub  }}</div>
  <div class="blue">This is {{ countReactive.author }}</div>

  <button v-on:click="increase">Increase</button>
  <form @submit="submitForm">
    <button type="submit">Increase now</button>
  </form> -->
</template>

<style>
  .blue{
    color: blue;
  }
</style>
