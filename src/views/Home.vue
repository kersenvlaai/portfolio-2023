<template>
  <Header />
  <div>hello, my name is {{ $route.meta.title }}</div>
</template>

<script setup>
import { useRouter } from "vue-router";
import Header from "../components/Header.vue";
const router = useRouter();
</script>
