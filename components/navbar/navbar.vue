<template>
  <div class="w-full bg-gray-900 text-gray-100">
    <div class="grid grid-cols-12 py-3">
      <nav-logo class="col-span-1" />
      <nav-search class="col-span-3" />
      <nav-item class="col-span-5" />
      <nav-control class="col-span-2" />
    </div>
  </div>
</template>

<script>
import navLogo from './navbar-components/nav-logo.vue'
import navSearch from './navbar-components/nav-search-bar.vue'
import navItem from './navbar-components/nav-item.vue'
import navControl from './navbar-components/nav-controle.vue'

export default {
  name: 'navbar',
  components: {
    navLogo,
    navSearch,
    navItem,
    navControl,
  },
}
</script>

<style></style>
