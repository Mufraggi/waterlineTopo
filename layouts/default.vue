<template>
  <div>
      <MyHeader />
      <Nuxt />
      <MyFooter style="padding-top: 50px" />
  </div>
</template>

<script>
import MyHeader from "~/components/myHeader";
export default {
name: "default",
  components: {MyHeader}
}
</script>

<style scoped>

</style>
