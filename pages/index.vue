<template>
  <div>
    <Car />
    <BeachHut />
  </div>
</template>

<script>
import Car from "../components/Car.vue";
import BeachHut from "../components/BeachHut.vue";

export default {
  name: "IndexPage",
  components: { Car, BeachHut },
};
</script>
