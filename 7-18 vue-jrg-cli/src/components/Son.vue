<template>
  <span>{{ message }}</span>
</template>
<script type="text/ecmascript-6">
  export default{
    data() {
      return {
        message: 'from component: son'
      }
    }
  }
</script>
<style scoped>
  span{
    color: #0f0;
  }
</style>