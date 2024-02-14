<template>
  <div class="card">
    <Menubar :model="items" />
  </div>
</template>

<script setup>
import { PrimeIcons } from "primevue/api";
import { ref } from "vue";

const items = ref([
  {
    label: "Home",
    icon: PrimeIcons.HOME,
  },
  {
    label: "Film Library",
    icon: PrimeIcons.LIST,
  },
  {
    label: "About",
    icon: PrimeIcons.INFO,
  },
  {
    label: "Contact",
    icon: "pi pi-envelope",
  },
]);
</script>
