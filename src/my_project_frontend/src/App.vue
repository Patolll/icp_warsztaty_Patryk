<template>
<div class = "container mx-auto flex flex-col items-center justify-center gap-16 px-2 border-solid bg-gray-700   ">
  <Header />
  <Calculator />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Calculator from "./components/Calculator.vue";
export default{
  name: "App",
  components:{
    Header,
    Calculator,
  },
};
</script>
