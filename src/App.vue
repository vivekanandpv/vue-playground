<template>
  <Playground />
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Playground from './components/Playground.vue';

export default defineComponent({
  name: 'App',
  components: {
    Playground
  }
});
</script>

<style>
</style>
