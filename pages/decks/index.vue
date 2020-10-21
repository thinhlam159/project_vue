<template>
  <div>
    <h1>Your decks, please enter number of deck to show</h1>
    <input type="text" v-model="deckID" placeholder="enter number of deck to show">
    <input type="button" @click="showDeck" value="Go to deck">
    <p>{{ deckID }}</p>
  </div>
</template>

<script>
  export default {
    name: "index",
    data() {
      return {
        deckID: ''
      }
    },
    methods: {
      showDeck: function () {
        this.$router.push(`/decks/${this.deckID}`)
      }
    }
  }
</script>

<style scoped>

</style>
