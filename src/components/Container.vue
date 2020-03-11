<template>
  <div class="container">
      <h1>Contatos</h1>
      <Cardcontact/>
  </div>
</template>

<script>
import Cardcontact from './Cardcontact.vue'

export default {
  name: 'Container',
  components: {
    Cardcontact
  }
}

</script>