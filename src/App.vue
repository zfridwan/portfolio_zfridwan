<template>
  <div id="app">
    <HeaderMe />
    <Tentangku />
    <Skillku />
    <Projectku />
    <Kontaku />
  </div>
</template>

<script>
// Correct imports, only import each component once
import HeaderMe from "./components/HeaderMe.vue";
import Tentangku from "./components/TentangMe.vue";
import Skillku from "./components/SkillMe.vue";
import Projectku from "./components/ProjectMe.vue";
import Kontaku from "./components/KontaMe.vue";

export default {
  components: {
    HeaderMe,  // Use consistent names
    Tentangku,
    Skillku,
    Projectku,
    Kontaku,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
