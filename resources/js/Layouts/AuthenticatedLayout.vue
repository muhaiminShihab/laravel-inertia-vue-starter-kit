<script setup>
import { ref } from "vue";
import { Link } from "@inertiajs/vue3";
import Sidebar from "../Components/Layouts/Sidebar.vue";
import Header from "../Components/Layouts/Header.vue";
</script>

<template>
    <!-- ===== Preloader Start ===== -->
    <!-- <include src="./partials/preloader.html"></include> -->
    <!-- ===== Preloader End ===== -->

    <!-- ===== Page Wrapper Start ===== -->
    <div class="flex h-screen overflow-hidden">
        <!-- ===== Sidebar Start ===== -->
        <Sidebar />
        <!-- ===== Sidebar End ===== -->

        <!-- ===== Content Area Start ===== -->
        <div
            class="relative flex flex-1 flex-col overflow-y-auto overflow-x-hidden"
        >
            <!-- ===== Header Start ===== -->
            <Header />
            <!-- ===== Header End ===== -->

            <!-- ===== Main Content Start ===== -->
            <main>
                <div class="mx-auto max-w-screen-2xl p-4 md:p-6 2xl:p-10">
                    <slot />
                </div>
            </main>
            <!-- ===== Main Content End ===== -->
        </div>
        <!-- ===== Content Area End ===== -->
    </div>
    <!-- ===== Page Wrapper End ===== -->
</template>
