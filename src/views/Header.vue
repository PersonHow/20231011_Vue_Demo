<script>
import { RouterLink, RouterView } from 'vue-router'
export default {
  components: {
    RouterLink
  }
}
</script>

<template>
  <nav class="topNav">

    <RouterLink class="cool" to="/">Home</RouterLink>
    <RouterLink to="/VtextAndVModel">V-text & V-Model</RouterLink>
  </nav>
</template>

<style lang="scss" scoped>
.topNav{
  width: 100%;
  height: 100%;
  background-color: #5d8369;
  font-size: 24pt;
  color: white;

}
</style>
