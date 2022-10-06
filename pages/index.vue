<template>
  <div>
    <TheComponent />
  </div>
</template>

<script>
import TheComponent from '../components/TheComponent.vue';
export default {
    name: "IndexPage",
    components: { TheComponent }
}
</script>

<style lang="scss">

@import "~/static/scss/main.scss";

</style>