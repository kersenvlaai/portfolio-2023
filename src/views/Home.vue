<template>
  <Header />
  <div>hello, my name is {{ $route.meta.title }}</div>
  <Experience />
</template>

<script setup>
import { useRouter } from "vue-router";
import Header from "../components/Header.vue";
import Experience from "../components/Experience.vue";
const router = useRouter();
</script>
