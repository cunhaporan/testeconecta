<template>
  <div>
    <Navbar/>
    <Container/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Container from './components/Container.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Container
  }
}
</script>

