<template>
  <nav class="app-nav">
    <ul>
      <RouterLink :to="{path: '/'}">
        Home
      </RouterLink>
      <RouterLink :to="{path: '/about'}">
        About
      </RouterLink>
      <RouterLink :to="{path: '/letters'}">
        Letters
      </RouterLink>
    </ul>
  </nav>
</template>

<script>
export default {}
</script>

<style lang="scss">
.app-nav {
  position: absolute;
  right: 135px;
}
</style>
