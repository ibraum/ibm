<template>
    <div class="w-full min-h-[100vh] relative bg-[linear-gradient(0deg,#242424,black,black)]">
        <NavBar />
        <Hero />
        <About />
        <Skills />
        <Projects />
        <Certificats />
        <Services />
    </div>
</template>

<script setup lang="ts">
    import NavBar from "../components/NavBar.vue";
    import Hero from "../components/Hero.vue";
    import About from "../components/About.vue";
    import Skills from "../components/Skills.vue";
    import Projects from "../components/Projects.vue";
    import Certificats from "../components/Certificats.vue";
    import Services from "../components/Services.vue";
</script>

<style scoped>
    
</style>