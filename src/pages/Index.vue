<template>
  <banner-component />
  <div class="row wrap justify-center">
    <div class="col-md-6 bg-gray-2 col-xs-12 flex wrap" style="height: 20rem;" >
      <div class="full-width p3 row items-center justify-center">
        <a href="/productos">
          <h4>Explorar Productos</h4>
        </a>
      </div>
    </div>
    <div class="col-md-6 col-xs-12 flex wrap">
      <div class="full-width p3 row items-center justify-center">
        <a href="/productos">
          <h4>Explorar Servicios</h4>
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import BannerComponent from 'components/BannerComponent.vue';
import { defineComponent, } from 'vue';

export default defineComponent({
  name: 'PageIndex',
  components: { BannerComponent },
  setup() {
    return;
  }
});
</script>
