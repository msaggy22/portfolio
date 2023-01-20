<script setup>
    defineProps({
        skills: Object,
        projects: Object,
    })
</script>


<template>
    <section id="portfolio" class="bg-light-primary dark:bg-dark-primary min-h[1400px]">
        <div class="container mx-auto">
            <div class="flex flex-col items-center text-center">
                <h2 class="section-title mt-4">My latest work</h2>
                <p class="subtitle">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Culpa praesentium non id quam quibusdam dolor autem, adipisci exercitationem aut sint?</p>
            </div>
        </div>
        <Projects :skills="skills" :projects="projects" />
    </section>
</template>