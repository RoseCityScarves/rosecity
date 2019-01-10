<template>
  <div class="home">
    <img alt="Soccer Scarf logo" src="../assets/borchers.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Landing from "@/components/Landing.vue";

export default {
  name: "home",
  components: {
    Landing
  }
};
</script>
