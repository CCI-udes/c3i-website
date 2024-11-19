<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h2>🤓🤓🤓🤓🤓🤓🤓🤓🤓 Get rotated nerd 🤓🤓🤓🤓🤓🤓🤓🤓🤓</h2>
    <img style="align-self: center;" src="../assets/fish-spinning.gif" alt="A spinning fish" />
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings {
  text-align: center;
  display: flex;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
