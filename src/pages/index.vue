<script setup lang="ts">
const router = useRouter()
</script>

<template>
  <h1 class="text-2xl m-5">Shadcn Vue Demo</h1>
  <main class="flex flex-col gap-4 ml-5 mr-5">
    <Button class="w-20" @click="router.push('/sidebar')">Sidebar</Button>
    <Button class="w-20" @click="router.push('/login')">Login</Button>
  </main>
</template>
