<template>
  <div class="home">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <!-- <img class="mx-auto" alt="Vue logo" src="../assets/logo.png" />
     -->
    <button class="text-start">click me</button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HomeView",
  components: {},
});
</script>
