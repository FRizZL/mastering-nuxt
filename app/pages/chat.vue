<script setup lang="ts">
const { chat, messages, sendMessage } = useChat();
</script>

<template>
    <chat-window :chat :messages @send-message="sendMessage" />
</template>
