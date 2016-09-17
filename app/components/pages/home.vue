<style lang="scss">
  @import 'app/common/utils/colors.scss';
  @import 'app/common/utils/media.scss';

  .Home {
    height: 100%;

    text-align: center;

  }

  .Home-container {
    margin: 0 20px;

    @include media(medium) {
      // margin: 0 50px;
    }

    @include media(large) {
      max-width: 1170px;
      margin: 0 auto;
    }
  }
</style>

<template>

  <div class="Home">
    <div class="Home-container">
      <header>

      </header>
    </div>
  </div>

</template>

<script>
  import Header from 'components/partials/header.vue';

  export default {
    name: 'Home',
    data() {
      return {
      };
    },
    components: {
      'header': Header
    }
  };
</script>
