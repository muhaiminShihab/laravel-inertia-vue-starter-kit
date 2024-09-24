<script setup>
import AuthenticatedLayout from "@/Layouts/AuthenticatedLayout.vue";
import { Head, usePage } from "@inertiajs/vue3";

console.log();
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2
                class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight"
            >
                Dashboard
            </h2>
        </template>

        <div class="py-12">
            <div class="w-full mb-2">
                <div
                    class="bg-white dark:bg-gray-800 overflow-hidden shadow-sm sm:rounded-lg"
                >
                    <div class="p-6 text-gray-900 dark:text-gray-100">
                        You're logged in, {{ usePage().props.auth.user.name }}!
                    </div>
                </div>
            </div>

            <div
                class="rounded-lg border border-stroke bg-white px-5 pb-2.5 pt-6 shadow-default dark:border-strokedark dark:bg-boxdark sm:px-7.5 xl:pb-1"
            >
                <div class="max-w-full overflow-x-auto">
                    <table class="w-full table-auto">
                        <thead>
                            <tr class="bg-gray-2 text-left dark:bg-meta-4">
                                <th
                                    class="min-w-[220px] px-4 py-4 font-medium text-black dark:text-white xl:pl-11"
                                >
                                    Package
                                </th>
                                <th
                                    class="min-w-[150px] px-4 py-4 font-medium text-black dark:text-white"
                                >
                                    Invoice date
                                </th>
                                <th
                                    class="min-w-[120px] px-4 py-4 font-medium text-black dark:text-white"
                                >
                                    Status
                                </th>
                                <th
                                    class="px-4 py-4 font-medium text-black dark:text-white"
                                >
                                    Actions
                                </th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 pl-9 dark:border-strokedark xl:pl-11"
                                >
                                    <h5
                                        class="font-medium text-black dark:text-white"
                                    >
                                        Free Package
                                    </h5>
                                    <p class="text-sm">$0.00</p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p class="text-black dark:text-white">
                                        Jan 13,2023
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p
                                        class="inline-flex rounded-full bg-success bg-opacity-10 px-3 py-1 text-sm font-medium text-success"
                                    >
                                        Paid
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    
                                    <details class="dropdown">
                                        <summary class="btn m-1">
                                            open or close
                                        </summary>
                                        <ul
                                            class="menu dropdown-content bg-base-100 rounded-box z-[1] w-52 p-2 shadow"
                                        >
                                            <li><a>Item 1</a></li>
                                            <li><a>Item 2</a></li>
                                        </ul>
                                    </details>
                                </td>
                            </tr>
                            <tr>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 pl-9 dark:border-strokedark xl:pl-11"
                                >
                                    <h5
                                        class="font-medium text-black dark:text-white"
                                    >
                                        Free Package
                                    </h5>
                                    <p class="text-sm">$0.00</p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p class="text-black dark:text-white">
                                        Jan 13,2023
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p
                                        class="inline-flex rounded-full bg-success bg-opacity-10 px-3 py-1 text-sm font-medium text-success"
                                    >
                                        Paid
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    
                                    <details class="dropdown">
                                        <summary class="btn m-1">
                                            open or close
                                        </summary>
                                        <ul
                                            class="menu dropdown-content bg-base-100 rounded-box z-[1] w-52 p-2 shadow"
                                        >
                                            <li><a>Item 1</a></li>
                                            <li><a>Item 2</a></li>
                                        </ul>
                                    </details>
                                </td>
                            </tr>
                            <tr>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 pl-9 dark:border-strokedark xl:pl-11"
                                >
                                    <h5
                                        class="font-medium text-black dark:text-white"
                                    >
                                        Free Package
                                    </h5>
                                    <p class="text-sm">$0.00</p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p class="text-black dark:text-white">
                                        Jan 13,2023
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p
                                        class="inline-flex rounded-full bg-success bg-opacity-10 px-3 py-1 text-sm font-medium text-success"
                                    >
                                        Paid
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    
                                    <details class="dropdown">
                                        <summary class="btn m-1">
                                            open or close
                                        </summary>
                                        <ul
                                            class="menu dropdown-content bg-base-100 rounded-box z-[1] w-52 p-2 shadow"
                                        >
                                            <li><a>Item 1</a></li>
                                            <li><a>Item 2</a></li>
                                        </ul>
                                    </details>
                                </td>
                            </tr>
                            <tr>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 pl-9 dark:border-strokedark xl:pl-11"
                                >
                                    <h5
                                        class="font-medium text-black dark:text-white"
                                    >
                                        Free Package
                                    </h5>
                                    <p class="text-sm">$0.00</p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p class="text-black dark:text-white">
                                        Jan 13,2023
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    <p
                                        class="inline-flex rounded-full bg-success bg-opacity-10 px-3 py-1 text-sm font-medium text-success"
                                    >
                                        Paid
                                    </p>
                                </td>
                                <td
                                    class="border-b border-[#eee] px-4 py-5 dark:border-strokedark"
                                >
                                    
                                    <details class="dropdown">
                                        <summary class="btn m-1">
                                            open or close
                                        </summary>
                                        <ul
                                            class="menu dropdown-content bg-base-100 rounded-box z-[1] w-52 p-2 shadow"
                                        >
                                            <li><a>Item 1</a></li>
                                            <li><a>Item 2</a></li>
                                        </ul>
                                    </details>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
