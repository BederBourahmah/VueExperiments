<template>
  <div class="home">
    <Login msg="Login" />
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Login from "@/components/Login.vue"; // @ is an alias to /src

export default Vue.extend({
  name: "Home",
  components: {
    Login
  }
});
</script>

<style lang="scss">
.home {
  background-color: #343a40;
}
</style>