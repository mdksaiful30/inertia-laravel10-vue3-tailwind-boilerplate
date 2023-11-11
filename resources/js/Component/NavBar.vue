<script setup>
import { Link } from '@inertiajs/vue3'

</script>

<template>
    <nav class="bg-gray-800">
        <div class="mx-auto max-w-7xl px-2 py-5 sm:px-6 lg:px-8">
                <div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start">
                    <div class="flex flex-shrink-0 items-center">
                        <img class="block lg:hidden h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-mark-indigo-500.svg" alt="Workflow">
                        <img class="hidden lg:block h-8 w-auto" src="https://tailwindui.com/img/logos/workflow-logo-indigo-500-mark-white-text.svg" alt="Workflow">
                    </div>
                    <div class="hidden sm:ml-6 sm:block">
                        <div class="flex space-x-4">
                            <!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
                            <Link  class="bg-gray-900 text-white rounded-md px-3 py-2 text-sm font-medium" href="/" aria-current="page">Home</Link >
                            <Link  class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium" href="/Page1">Page1</Link >
                            <Link  class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium" href="/Page2">Page2</Link >
                            <Link  class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium" href="/Page3">Page3</Link >
                            <Link  class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium" href="/Page4">Page4</Link >
                            <Link  class="text-gray-300 hover:bg-gray-700 hover:text-white rounded-md px-3 py-2 text-sm font-medium" href="/Page5">Page5</Link >

                        </div>
                    </div>
                </div>
        </div>
    </nav>

</template>
