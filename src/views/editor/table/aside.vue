<template lang="pug">
  el-aside(style="background-color: rgb(238, 241, 246)") table-aside
</template>

<script>
  export default {
    mounted() {
      console.log(this.$route.params)
    }
  }
</script>
