<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <img
        src="https://img.shoprocket.io/cdn-cgi/image/w=700,h=700,quality=75/bt8khmye-avatar.png"
        alt="Shoprocket"
        class="logo"
      />
    </template>
    <template #heading>Shoprocket - start selling online</template>

    All the tools you'll need to sell from your existing website, social
    channels and more, with no technical skills required.
    <a href="https://shoprocket.io/register" target="_blank" rel="noopener">
      Start 14 Day Free Trial ➞
    </a>
  </WelcomeItem>
</template>

<style scoped>
.logo {
  width: 30px;
}
</style>
