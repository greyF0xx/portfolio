<template>
  <div>
    <div v-if="firstp">Bienvenue
      
    </div>
    <div v-else><nuxt /></div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      firstp: true,
    };
  },
};
</script>

<style></style>
