<template>
  <section id="projects">
    <h2>Projects</h2>
    <div v-for="project in projects" :key="project.id">
      <h3>{{ project.name }}</h3>
      <p>{{ project.description }}</p>
      <a :href="project.link" target="_blank">View Project</a>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      projects: [
        {
          id: 1,
          name: "Mobile Banking App",
          description:
            "A fully functional banking application for Android and iOS.",
          link: "https://github.com/your-profile/mobile-banking-app",
        },
        {
          id: 2,
          name: "E-commerce Website",
          description: "An online store with secure payment integration.",
          link: "https://github.com/your-profile/e-commerce-website",
        },
      ],
    };
  },
};
</script>

<style scoped>
#projects {
  padding: 20px;
  background-color: #fff;
}
</style>
