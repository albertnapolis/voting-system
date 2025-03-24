<template>
  <div class="main-container w-100 h-100">
    <dashboard-view />
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import DashboardView from './views/DashboardView.vue';

  export default defineComponent({
    components: { DashboardView },
    setup() {

      return {}
    }
  })
</script>

<style>

</style>
