<template>
  <div class="grid">
    <div class="col-12">
      <layout-header/>
    </div>
    <div class="col-12">
      <router-view/>
    </div>
  </div>
</template>

<script lang="ts">
import LayoutHeader from "@/app/layout/components/LayoutHeader.vue";

export default {
  name: "Layout",
  components: {LayoutHeader}
}
</script>

<style scoped>

</style>