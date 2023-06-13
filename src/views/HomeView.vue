<template>
  <div class="null">
    <!-- <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav> -->

    <div class="relative md:ml-64">
      <navbar-view />
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import NavbarView from "@/components/NavbarView.vue";

export default defineComponent({
  name: "HomeView",
  components: {
    NavbarView,
  },
});
</script>
