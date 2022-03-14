<template>

      <div class="album-wrapper">

        <div class="card">

          <figure class="card__thumb">
            <!-- <img src="../assets/img/logo.png" alt=""> -->
          </figure>

          <h1 class="card__title">
            New jersey
          </h1>

          <span class="card__name">
            Bon Jovi
          </span>

          <span class="card__age">
            1988
          </span>

        </div>

      </div>

</template>

<script>
    export default {
        name:'AlbumCard',
    }
</script>

<style lang="scss" scoped>

    .album-wrapper {
      display: flex;
      flex-wrap: wrap;
      gap: 40px;

      .card {
        display: flex;
        flex-direction: column;
        background-color: #2E3A46;
        height: 355px;
        width: 198px;

        .card__title {
          color: white;
          text-transform: uppercase;
          margin-bottom: 20px;
          margin-top: 20px;
        }

        .card__thumb {

          img {
            display: block;
            aspect-ratio: 1/1;
            width: 100%;
            object-fit: cover;
            object-position:center;
          }
        }

        .card__name {
          color: gray;
          font-size: 18px;
        }

        .card__age {
          color: gray;
          font-size: 18px;
        }
      }
    }
</style>