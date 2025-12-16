<script setup lang="ts">
const { chat, messages, sendMessage } = useChat();

useHead({
    title: chat.value.title,
});
</script>

<template>
    <chat-window :chat :messages @send-message="sendMessage" />
</template>
