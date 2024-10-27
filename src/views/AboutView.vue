<script setup>
  import { useRouter } from 'vue-router';
  const router = useRouter();
</script>

<template>
  <div class="about">
    <!-- <button @click="router.push({ name: 'user'})">Direct to user</button> -->
    <RouterLink to="/about/user">Direct to user</RouterLink>
    <router-view></router-view>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
