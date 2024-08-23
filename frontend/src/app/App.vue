<template lang="pug">
router-view
</template>

<script setup lang="ts">
defineOptions({
  name: 'App',
});

// import Client, { Local } from 'src/app/client'

// // Making request to locally running backend...
// const client = new Client(Local);
// const func = async () => {
//   const result = await client.hello.get('test')
//   console.log("RESULT: ", result)
// }

// func()
</script>
