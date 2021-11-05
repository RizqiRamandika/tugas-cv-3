<template>
  <div id="app">
    <div class="row py-4">
      <project-1 />
      <div>
        <h1 style="text-align: center">CV-2</h1>
        <project-2 />
      </div>
    </div>
  </div>
</template>

<script>
import Project1 from "./components/Project1.vue";
import Project2 from "./components/Project2.vue";

export default {
  name: "app",
  components: {
    Project1,
    Project2,
  },
};
</script>