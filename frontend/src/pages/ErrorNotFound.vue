<template lang="pug">
div.fullscreen.bg-blue.text-white.text-center.q-pa-md.flex.flex-center
  div
    div(style="font-size: 30vh")
      404

    div(style="opacity:.4").text-h2
      p Oops. Nothing here...

    q-btn(
      class="q-mt-xl"
      color="white"
      text-color="blue"
      unelevated
      to="/"
      label="Go Home"
      no-caps
    )
</template>

<script setup lang="ts">
defineOptions({
  name: 'ErrorNotFound',
});
</script>
