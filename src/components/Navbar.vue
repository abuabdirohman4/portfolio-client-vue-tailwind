<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <nav
    class="rounded border-gray-200 bg-white px-5 py-2.5 dark:bg-gray-800 sm:px-4"
  >
    <div
      class="container mx-auto my-2 flex flex-wrap items-center justify-between"
    >
      <!-- Logo -->
      <RouterLink to="/" class="flex items-center">
        <img
          src="@/assets/img/logo.svg"
          class="ml-3 h-8 sm:ml-0 sm:h-8"
          alt="Flowbite Logo"
        />
      </RouterLink>
      <!-- Menu -->
      <div
        class="hidden w-full items-center justify-between md:order-1 md:flex md:w-auto"
        id="mobile-menu-2"
      >
        <ul
          class="md:font-regular mt-4 flex flex-col md:mt-0 md:flex-row md:space-x-8 md:text-sm"
        >
          <li>
            <RouterLink
              to="/"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              aria-current="page"
              >Home</RouterLink
            >
          </li>
          <li>
            <a
              href="#about"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              >About Me</a
            >
          </li>
          <li>
            <RouterLink
              to="/skills"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              >Skills</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/portfolio"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              >Portfolio</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/article"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              >Article</RouterLink
            >
          </li>
          <li>
            <RouterLink
              to="/contact"
              class="block border-b border-gray-100 py-2 pl-3 pr-4 text-gray-700 hover:bg-gray-50 dark:border-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:border-0 md:p-0 md:hover:bg-transparent md:hover:text-indigo-600 md:dark:hover:bg-transparent md:dark:hover:text-white"
              >Contact</RouterLink
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
