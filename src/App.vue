<template>
  <div></div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    if ("alt" in window) {
      alt.emit("ClientWEB:PhoneWebView:Ready");
    }
  }
}
</script>

<style>
</style>
