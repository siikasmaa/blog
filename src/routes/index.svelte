<style lang="scss">
  .home {
    &-container {
      align-items: center;
      display: flex;
      flex: 1;
      justify-content: center;
      margin: 2em 0;
      min-height: 400px;
    }
  }
  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  figure {
    margin: 2em 2em;
    text-align: center;
  }
  img {
    width: 200px;
    max-width: 400px;
    border-radius: 50%;
  }
  @media (max-width: 1020px) {
    img {
      max-width: 300px;
    }
  }
  @media (max-width: 800px) {
    .home {
      &-container {
        flex-direction: column;
      }
      &-copy {
        flex: 0;
        padding-bottom: 2em;
        text-align: center;
      }
    }
  }
</style>

<svelte:head>
  <title>Siika writes</title>
</svelte:head>

<div class="home-container">
  <figure>
    <img alt="Profile" src="profile_2.svg" />
  </figure>
  <div class="home-copy">
    <h1>Siika writes a blog</h1>
  </div>

</div>
