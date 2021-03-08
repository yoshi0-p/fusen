<template>
    <div>
      <div id="navi"><HeaderMenu /></div>
      <img src="https://pbs.twimg.com/media/Eu-89xbUcAAFvTB?format=jpg&amp;name=900x900" alt="">
      <Message />
      </div>
</template>

<script>
import HeaderMenu from "../components/HeaderMenu";
import Message from "../components/Message";
export default {
  components: {
    HeaderMenu,
    Message
  }
};
</script>
