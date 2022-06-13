<template>
  <Header />
  <router-view />
</template>

<style>
body {
  margin: 0;
  padding: 0;
}

.container {
  width: 75%;
  padding: 10px;
  margin-left: auto;
  margin-right: auto;
}

@media (min-width: 601px) and (max-width: 800px) {
  .container {
    width: 95%;
  }
}

@media (max-width: 600px) {
  .container {
    width: 100%;
  }
}
</style>

<script>
import Header from "@/components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
  },
};
</script>
