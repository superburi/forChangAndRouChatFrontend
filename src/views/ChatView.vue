<script setup>

    import ChatRoom from '../components/ChatRoom.vue'
    import ChatInput from '../components/ChatInput.vue'

</script>

<template>
    <div class="chat">
      <!--
      <h1>This is an about page</h1>
      -->
      <ChatRoom class="chat-room" ></ChatRoom>
      
      <ChatInput class="chat-input" ></ChatInput>
    </div>
</template>

<style>

    @media (min-width: 1024px) { /* 原本是 min-width: 1024px */

        .chat {
            min-height: 95vh;
            display: flex;
            flex-direction: column;
            align-items: stretch; /* 原本是 center */
            gap: 10px;
        }

        .chat-room {
            flex: 15;
        }

        .chat-input {
            flex: 1;
        }

    }

</style>
  