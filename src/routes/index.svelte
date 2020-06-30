<style lang="postcss">
  h1,
  figure,
  p {
    @apply text-center m-auto;
  }

  img {
    @apply text-center w-full max-w-xl mb-2 inline;
  }

  p {
    @apply my-4 mx-auto;
  }

  @screen lg {
    h1 {
      @apply text-4xl;
    }
  }
</style>

<svelte:head>
  <title>Sapper project template</title>
</svelte:head>

<h1 class="text-2xl uppercase font-bold mb-2">Great success!</h1>

<figure>
  <img alt="Success Kid" src="successkid.jpg" />
  <figcaption>Have fun with Sapper!</figcaption>
</figure>

<p>
  <strong>
    Try editing this file (src/routes/index.svelte) to test live reloading.
  </strong>
</p>
