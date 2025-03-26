<template>
  <div class="main-container w-100 h-100">
    <!-- <dashboard-view /> -->
    <!-- <login-view /> -->
    <voting-view />
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import DashboardView from './views/DashboardView.vue';
  import LoginView from './views/LoginView.vue';
  import VotingView from './views/VotingView.vue';

  export default defineComponent({
    components: { VotingView },
    setup() {

      return {}
    }
  })
</script>

<style>

</style>
