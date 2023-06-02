<script setup>

</script>

<template>
    <!-- ======= Navigation ======= -->
    <nav class="flex flex-wrap relative mx-auto">
        <nav class="flex justify-between bg-gray-900 text-white w-screen">
            <div class="px-5 xl:px-12 py-6 flex w-full items-center">
                <a class="text-3xl font-bold font-heading" href="#">
                    Glen Buecker
                </a>
                <!-- Nav Links -->
                <ul class="hidden md:flex px-4 mx-auto font-semibold font-heading space-x-12">
                    <li><a class="hover:text-gray-200 scrollto active" href="#hero">Home</a></li>
                    <li><a class="hover:text-gray-200 scrollto" href="#about">About Me</a></li>
                    <li><a class="hover:text-gray-200 scrollto" href="#transferable-skills">Transferable Skills</a></li>
                    <li><a class="nhover:text-gray-200 scrollto " href="#portfolio">Portfolio</a></li>
                </ul>

            </div>
            <!-- Responsive navbar -->
            <a class="navbar-burger self-center mr-12 md:hidden" href="#">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 hover:text-gray-200" fill="none"
                     viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                </svg>
            </a>
        </nav>
    </nav>
</template>

<style scoped>

</style>
