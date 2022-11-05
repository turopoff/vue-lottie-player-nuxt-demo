<template>
  <client-only>
    <v-lottie-player
      name="shapeAnimation"
      loop
      :animation-data="require('../assets/shape-animation.json')"
    />
  </client-only>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
