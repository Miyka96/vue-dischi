<template>
  <section>
    
    <div class="container">

      <AlbumCards/>

    </div>

  </section>
</template>

<script>
import AlbumCards from './AlbumCards.vue'

export default {
  name: 'MainContent',
  components: {
    AlbumCards,
  }
  
}
</script>

<style scoped lang="scss">

section {
  height:867px;
  background-color: #1E2D3B;
  padding-top: 70px;

  .container {
    max-width: 1152px;
    margin: 0 auto;

  }
}

</style>
