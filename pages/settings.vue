<template>
  <div class="page">
    <div class="nav">
      <ul>
        <li>
          <nuxt-link to="/settings">Settings</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/deck">Deck</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/settings/schedule">Schedule</nuxt-link>
        </li>
      </ul>
    </div>
    <nuxt-child></nuxt-child>
  </div>
</template>

<script>
    export default {
        name: "settings"
    }
</script>

<style scoped lang="scss">
  .page {
    display: flex;
  }
  .general {
    margin-left: 30px;
  }
</style>
