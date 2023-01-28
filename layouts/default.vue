<script lang="ts" setup>
import Header from '~~/components/App/Header.vue';

</script>

<template>

<div>
  <AppHeader/>
  <div class="px-4 mx-auto sm:px-0">
    <slot />
  </div>
 
  <AppFooter/>
</div>
</template>

<style scoped></style>
