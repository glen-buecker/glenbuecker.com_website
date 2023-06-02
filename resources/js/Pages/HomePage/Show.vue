<script setup>
import Layout from "./Layout.vue";
import { Head } from "@inertiajs/vue3";
import Hero from "./Partials/Hero.vue";
import Technologies from "./Partials/Technologies.vue";
import AboutMe from "./Partials/AboutMe.vue";
import TransferableSkills from "./Partials/TransferableSkills.vue";
import Portfolio from "./Partials/Portfolio.vue";
import Projects from "./Partials/Projects.vue";
import Footer from "./Partials/Footer.vue";
</script>

<template>
    <Layout>
        <Head>
            <meta charset="utf-8" />
            <meta
                content="width=device-width, initial-scale=1.0"
                name="viewport"
            />
            <meta
                name="description"
                content="A website showcasing the web skills of Glen Buecker"
            />
            <meta
                name="keywords"
                content="HTML, CSS, JavaScript, PHP, node.js, jQuery, Laravel, Vite, Vue, React"
            />
        </Head>
        <Hero />
        <Technologies />
        <AboutMe />
        <TransferableSkills />
        <Portfolio />
        <Projects />
        <Footer />

       
    </Layout>
</template>
