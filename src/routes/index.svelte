<style>
  .home-container {
    align-items: center;
    display: flex;
    flex: 1;
    justify-content: center;
    margin: 2em 0;
    min-height: 400px;
  }
  .home-copy {
    flex: 1;
  }
  h1 {
    font-weight: 700;
    margin-bottom: 0.5em;
  }

  figure {
    margin: 0 1em;
    text-align: center;
  }
  figcaption {
    font-size: 0.8em;
    font-style: italic;
  }
  img {
    width: 100%;
    max-width: 400px;
  }
  @media (max-width: 1020px) {
    img {
      max-width: 300px;
    }
  }
  @media (max-width: 800px) {
    .home-container {
      flex-direction: column;
    }
    .home-copy {
      flex: 0;
      padding-bottom: 2em;
      text-align: center;
    }
  }
</style>

<svelte:head>
  <title>Siika writes</title>
</svelte:head>

<div class="home-container">
  <div class="home-copy">
    <h1>Siika writes a blog</h1>
  </div>

  <figure>
    <img alt="Person typing on laptop" src="undraw-illustration.svg" />
    <figcaption>
      Illustration from
      <a href="https://undraw.co" target="_blank">Undraw</a>
    </figcaption>
  </figure>
</div>
