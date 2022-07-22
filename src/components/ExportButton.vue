<template>
  <v-btn
    rounded
    outlined
    color="success"
    href="http://localhost:8000/api/export"
    download
    style="position: fixed;bottom: 100px;right: 100px"
  >Export DB</v-btn>
</template>

<script>
export default {
  name: 'ExportButton'
}
</script>

<style scoped>

</style>
