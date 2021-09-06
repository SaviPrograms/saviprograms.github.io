<template>
  <div>
    <h1>Zażółć Gęślą jaźń</h1>
    <wave-intro-divider/>
  </div>
</template>

<script>
import waveIntroDivider from '~/components/wave-intro-divider.vue';

export default {
  components: { waveIntroDivider }
}
</script>

<style lang="scss">

body{
  width: 100vw;
  height: 100vh;
  background-color: var(--c-bg-primary);
  color: var(--c-accent-secondary);
}
</style>
