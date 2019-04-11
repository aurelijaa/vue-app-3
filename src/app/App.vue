<template>
  <div id="app">
    <AppHeader />
    <AppContainer />
    <AppWhiteBox />
    <RouterView />
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader'
import AppContainer from '@/components/AppContainer'
import AppWhiteBox from '@/components/AppWhiteBox'

export default {

  name: 'App',
  components: {
    AppHeader,
    AppContainer,
    AppWhiteBox
  }
}
</script>
