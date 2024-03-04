<template>
  <div>
    <q-btn label="login" />

    <q-input type="email" v-model="email" />

    <q-input type="password" v-model="password" />
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const email = ref();
const password = ref();
</script>
