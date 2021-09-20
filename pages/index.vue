<template>
  <div>
    <div>
      <navbar />
    </div>
    <div>
      <tab />
    </div>
  </div>
</template>

<script>
import navbar from '~/components/navbar/navbar.vue'
import tab from '~/components/tab-components/tab.vue'
export default {
  components: { navbar, tab },
}
</script>
<style>
body {
  background-color: #0d1117;
}
</style>
