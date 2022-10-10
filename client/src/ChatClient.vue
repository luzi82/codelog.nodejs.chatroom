<template>
  <main>
    Hello World
    <button @click="asdfOnClick">ASDF</button>
  </main>
</template>

<script>
export default {
  data() {
    let ws = new WebSocket('ws://localhost:3000');
    return {
      ws: ws,
    };
  },
  methods: {
    asdfOnClick(event) {
      console.log('asdf');
    },
  },
}
</script>
