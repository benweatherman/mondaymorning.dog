<style>
  h1,
  figure,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h1 {
    font-size: 2.8em;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 0.5em 0;
  }

  figure {
    margin: 0 0 1em 0;
  }

  img {
    width: 100%;
    max-width: 400px;
    margin: 0 0 1em 0;
  }

  p {
    margin: 1em auto;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
</style>

<svelte:head>
  <title>Dogs on Monday Morning</title>
</svelte:head>

<h1>Dog</h1>

<div
  class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img
        class="h-48 w-full object-cover md:w-48"
        src="/img/chewy.jpg"
        alt="Sprout" />
    </div>
    <div class="p-8">
      <div
        class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">
        Sprouts
      </div>
      <a
        href="#"
        class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Small,
        mighty, and beautiful</a>
      <p class="text-left mt-2 text-gray-500">
        Even when it's cold outside, I make it beautiful to look at.
      </p>
    </div>
  </div>
</div>

<div
  class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img
        class="h-48 w-full object-cover md:w-48"
        src="/img/sprout.jpg"
        alt="Sprout" />
    </div>
    <div class="p-8">
      <div
        class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">
        Sprout
      </div>
      <a
        href="#"
        class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">Redefining
        what it means to be a basic bitch</a>
      <p class="text-left mt-2 text-gray-500">
        Don't let the ears fool you: I'm not here to listen to your bullshit.
      </p>
    </div>
  </div>
</div>

<div
  class="max-w-md mx-auto bg-white rounded-xl shadow-md overflow-hidden md:max-w-2xl">
  <div class="md:flex">
    <div class="md:flex-shrink-0">
      <img
        class="h-48 w-full object-cover md:w-48"
        src="/img/molly.jpg"
        alt="Molly" />
    </div>
    <div class="p-8">
      <div
        class="uppercase tracking-wide text-sm text-indigo-500 font-semibold">
        Molly
      </div>
      <a
        href="#"
        class="block mt-1 text-lg leading-tight font-medium text-black hover:underline">The
        spunky new queen on the block</a>
      <p class="text-left mt-2 text-gray-500">
        I'm here to bring joy to the world and pee to your couch.
      </p>
    </div>
  </div>
</div>
