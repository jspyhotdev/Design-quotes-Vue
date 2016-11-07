<template>
  <footer class="footer">
    <div class="container" v-once>
      <p class="text-muted text-center">
        Built by <a href="https://mikesprague.me" target="_blank">Mike Sprague</a>.
        <br>
        Source <i class="fa fa-code"></i> available on <a href="{{ link }}" target="_blank"><i class="fa fa-github"></i> GitHub</a>.
      </p>
    </div>
  </footer>
</template>

<script>
  export default {
    name: "fixed-footer",
    props: ["link"]
  }
</script>

<style scoped>
  .footer {
    position: absolute;
    bottom: 0;
    width: 100%;
    height: 60px;
  }
</style>
