<template>
  <div>hi</div>
</template>

<script>
export default {
  asyncData() {
    $nuxt.$fire.auth.signOut()
  }
}
</script>

<style>

</style>
