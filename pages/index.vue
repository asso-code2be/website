<template>
  <div class="container">
    <div>
      <card />
    </div>
  </div>
</template>

<script>
import Card from '~/components/Card.vue'

export default {
  components: {
    Card
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
