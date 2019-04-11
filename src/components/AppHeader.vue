<template>
  <div class="app-header-wraper">
    <header class="app-header">
      <div class="app-header__content">
        <h1> Vardas Pavarde</h1>
        <h3>Portfolio</h3>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>

<style lang="scss">

 .app-header-wraper {
background-color: royalblue;
height: 50vh;
width: 100%;
  }

.app-header {
  display: flex;
align-items: center;
justify-content: center;
width: 100%;
height: 100%;
&__content{
  color:white;
  text-transform: uppercase;
  text-align: center;
}
}

</style>
