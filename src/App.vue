<template>
  <twitch-player
    :channel="channel"
  ></twitch-player>
</template>

<script>
  import VueTwitchPlayer from 'vue-twitch-player';

  export default {
    // ...
    components: {
      VueTwitchPlayer,
    },
    data() {
      return {
        channel: 'me8robot',
      };
    },
    // ...
  };
</script>
