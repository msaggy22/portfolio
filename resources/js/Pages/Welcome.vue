<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';
import FrontendLayout from '@/Layouts/Frontend.vue';
import Hero from '@/Components/Frontend/Hero.vue';
import Promote from '@/Components/Frontend/Promote.vue';
import About from '@/Components/Frontend/About.vue';


</script>

<template>
    <Head title="Welcome to Portfolio" />
    <FrontendLayout>
        <!-- Hero primary -->
        <Hero/>
        <!-- Promote tail-100 -->
        <Promote/>
        <!-- About Secondary -->
        <About/>
        <!-- Skills tail-100 -->
        <!-- Portfolio Primary -->
        <!-- Services secondary -->
        <!-- Contact primary -->
    </FrontendLayout>
</template>
