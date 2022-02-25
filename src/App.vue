<script setup lang="ts">
import TheHeader from "@/components/TheHeader.vue";
import EntryEditor from "./components/EntryEditor.vue";
import EntryList from "./components/EntryList.vue";
</script>

<template>
  <main class="container m-auto p-10">
    <TheHeader />
    <EntryEditor />
    <EntryList />
  </main>
</template>
