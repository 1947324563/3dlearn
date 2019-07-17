<template lang="pug">
  .city 上海
  <div class="home" id="home">

  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
  },
})
export default class Home extends Vue {
    camera: null | undefined;
    scene: number = 123;
    renderer: null | undefined ;
    mesh: null | undefined;

}
</script>
<style lang="scss">
  .city {
    color: red;
  }
</style>
