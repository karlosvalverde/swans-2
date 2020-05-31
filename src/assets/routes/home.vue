<template>
  <div class="home full">
    <div class="my-auto">
      <h1 class="is-big">Hardest band on Earth<br>
      <span class="is-secondary">Live<br>
      30. 06. 20</span><br>
      Bar<br>
      Celona</h1>
    </div>
    <div class="h-full">
      <v-lazy-image class="w-full my-auto z-0" src="https://i.imgur.com/xOftcX9.jpg" />
    </div>
  </div>
</template>

<script>
import VLazyImage from "v-lazy-image";

export default {
  name: "home",
  components: {
    VLazyImage
  }
};
</script>
