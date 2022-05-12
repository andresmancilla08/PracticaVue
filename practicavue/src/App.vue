<template>
  <div class="px-4 bg-page">
    <Login></Login>
  </div>
</template>

<script>
import Login from "./components/login.vue";
import "./assets/css/tailwind.css";

export default {
  name: "App",
  components: {
    Login,
  },
};
</script>

<style>
@import "./assets/css/styles.css";
.bg-page {
  background-image: url("~@/assets/images/fondo-vue.jpeg");
}
</style>
