<template>
  <div id="app" class="flex flex-col min-h-screen">
    <Nav />
    <router-view/>
  </div>
</template>
<script>
import Nav from './components/Nav'
export default {
  components: {
    Nav
  }
}
</script>
<style>
</style>