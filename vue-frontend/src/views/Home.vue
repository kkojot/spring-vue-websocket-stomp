<template>
  <div class="home">
    <websocket-greetings></websocket-greetings>
  </div>
</template>

<script>
// @ is an alias to /src
import WebsocketGreetings from "@/components/WebsocketGreetings.vue";

export default {
  name: "home",
  components: {
    WebsocketGreetings
  }
};
</script>
