<template>
  <div >
<app-nav></app-nav>
<app-home></app-home>
  </div>
</template>

<script>
import Home from './component/home.vue'
export default {
  components: {
    'app-home': Home
  }
}
</script>

<style >
  @import '/assets/bootstrap.min.css';
</style>
