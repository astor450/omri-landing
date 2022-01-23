<template>
  <router-view />
</template>
<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App'
})
</script>

<style lang="scss">
  .p1{
    padding: 0.25rem 0.25rem 0.25rem 0.25rem;
  }
  .p2{
    padding: 0.5rem 0.5rem 0.5rem 0.5rem;
  }
  .p3{
    padding: 1rem 1rem 1rem 1rem;
  }
  .p4{
    padding: 2rem 2rem 2rem 2rem;
  }
  .p2{
    padding: 3rem 3rem 3rem 3rem;
  }
</style>
