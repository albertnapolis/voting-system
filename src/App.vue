<template>
  <div class="main-container w-100 h-100">
    <login-view />
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import LoginView from './views/LoginView.vue';

  export default defineComponent({
    components: { LoginView },
    setup() {

      return {}
    }
  })
</script>

<style>

</style>
