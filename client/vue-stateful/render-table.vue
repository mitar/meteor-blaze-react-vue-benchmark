<template>
  <table>
    <tbody>
      <render-table-row v-for="doc in content" :row="doc.row" :key="doc._id" />
    </tbody>
  </table>
</template>

<script>
  export default {
    props: ['content']
  }
</script>