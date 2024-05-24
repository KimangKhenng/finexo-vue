<template>
  <div class="bg">
    <flex-header />
  </div>
</template>

<script>
import FlexHeader from "@/components/FlexHeader.vue";
export default {
  components: {
    FlexHeader,
  },
  name: "App",
};
</script>
<style scoped>
.bg {
  background-color: blue;
}
</style>