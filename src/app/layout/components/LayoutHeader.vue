<template>
  <p-toolbar>
    <template #start>
      <h2>IT Employee</h2>
    </template>
    <template #end>
      <p-button icon="pi pi-calendar" class="p-button-success mr-2" />
    </template>
  </p-toolbar>

  <div class="p-panel p-panel-header">
      Avatar - Username
  </div>
  <!--
  <div class="grid">
    <div class="col-2">
      <h1>IT Employee</h1>
    </div>
    <div class="col-8">
      Middle row
    </div>
    <div class="col-2">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </div>
  </div>
  -->
</template>

<script>
export default {
  name: "LayoutHeader"
}
</script>

<style scoped>
</style>
