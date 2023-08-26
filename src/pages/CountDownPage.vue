<template>
  <q-page padding>
    <h5>Countdown</h5>
    <div>
      <span class="digit">{{ hour }}</span>
      <span class="digit">{{ min }}</span>
      <span class="digit">{{ sec }}</span>
    </div>
  </q-page>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue';

const hour = ref(0);
const min = ref(5);
const sec = ref(0);
</script>

<style>
.digit {
  border: 1px solid red;
  margin: 3px;
}
</style>
