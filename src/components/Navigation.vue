<template>
  <header class="bg-at-light-green text-white">
    <nav class="container py-5 px-4 flex flex-col gap-4 items-center sm:flex-row">
      <div class="flex items-center gap-x-4">
        <img class="w-14 " src="../assets/images/dumbbell-light.png" alt="">
        <h1 class="text-lg">Tracker</h1>
      </div>
      <ul class="flex flex-1 justify-end gap-x-10">
        <router-link class="cursor-pointer" :to="{name: 'Home'}">Home</router-link>
        <router-link class="cursor-pointer" :to="{name: 'Home'}">Create</router-link>
        <router-link class="cursor-pointer" :to="{name: 'Login'}">Log In</router-link>
        <li class="cursor-pointer">Log Out</li>
      </ul>

    </nav>
  </header>
</template>

<script>
export default {
  setup() {
    // Get user from store

    // Setup ref to router

    // Logout function

    return {};
  },
};
</script>
