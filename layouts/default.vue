<template>
  <div>
    <sidebar />
    <nuxt />
  </div>
</template>

<script>
import sidebar from '~/components/SideBar'

export default {
  components: {
    sidebar
  }
};
</script>

<style>

sidebar {
  position: fixed;
}

</style>
