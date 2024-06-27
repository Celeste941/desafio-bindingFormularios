<template>
  <DatosTarjeta />
</template>

<script>
import DatosTarjeta from "./components/DatosTarjeta.vue";

export default {
  name: "App",
  components: {
    DatosTarjeta,
  },
};
</script>

<style>
body{
display: flex;
justify-content: center;
margin-top: 150px;
}
</style>
