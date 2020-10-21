<template>
  <div class="container">
    <!--    <div>-->
    <!--      <Logo />-->
    <!--      <h1 class="title">-->
    <!--        ThinhLam-->
    <!--      </h1>-->
    <!--      <div class="links">-->
    <!--        <a-->
    <!--          href="https://nuxtjs.org/"-->
    <!--          target="_blank"-->
    <!--          rel="noopener noreferrer"-->
    <!--          class="button&#45;&#45;green"-->
    <!--        >-->
    <!--          Documentation-->
    <!--        </a>-->
    <!--        <a-->
    <!--          href="https://github.com/nuxt/nuxt.js"-->
    <!--          target="_blank"-->
    <!--          rel="noopener noreferrer"-->
    <!--          class="button&#45;&#45;grey"-->
    <!--        >-->
    <!--          GitHub-->
    <!--        </a>-->
    <!--      </div>-->
    <!--    </div>-->
    <header>
      <nav>
        <ul>
          <li>
            <nuxt-link to="/">Home</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/decks">Decks</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/profile">Profile</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/settings">Settings</nuxt-link>
          </li>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>
  export default {}
</script>

<style>
  .container {
    margin: 0 auto;
    /*display: flex;*/
    /*justify-content: center;*/
    /*align-items: center;*/
    text-align: center;
  }

  .title {
    font-family: 'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
    display: block;
    font-weight: 300;
    font-size: 100px;
    color: #35495e;
    letter-spacing: 1px;
  }

  .subtitle {
    font-weight: 300;
    font-size: 42px;
    color: #526488;
    word-spacing: 5px;
    padding-bottom: 15px;
  }

  .links {
    padding-top: 15px;
  }
</style>
