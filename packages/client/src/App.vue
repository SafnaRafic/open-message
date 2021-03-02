<template>
  <login />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import "bootstrap/dist/css/bootstrap.css";
import Login from "./pages/login.vue";

@Options({
  components: {
    Login,
  },
})
export default class App extends Vue {}
</script>

<style>
* {
  box-sizing: border-box;
}

body {
  display: flex;
  font-weight: 400;
}
img.logo {
  width: 20%;
  position: absolute;
  top: 8px;
  left: 10px;
  margin: 20px;
}
</style>
