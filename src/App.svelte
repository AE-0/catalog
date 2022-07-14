<script>
  //import logo from './assets/svelte.png'
  //mport Counter from './lib/Counter.svelte'
</script>

<main>
  <!--img src={logo} alt="Svelte Logo" /-->
  <div class="navbar">
    <a class="logo" href="/">
      <h1>Mi Mundo Creativo</h1>
    </a>
    <div class="space"></div>
    <a class="idk" href="/">
      boton
    </a>
  </div>
  <div class="carousel">
    <img src="./src/assets/1.jpg" alt="">
  </div>
  <!--Counter/-->

  <p>
    Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte
    apps.
  </p>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  :root {
  --color1: #FBFAFA;
  --color2: #DFBFA5;
  --color3: #B3B1C1;
  --color4: #9E899D;
  --color5: #2F9A56;
  --primary: #b3b1c1;
  --info: #2f9a56;
  --success: #6bb072;
  ---warning: #e8a03a;
  --danger: #f44336;
  --shadow: 0 16px 38px -12px rgba(0, 0, 0, 0.56), 0 4px 25px 0px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.2);
  --shadow2: 0 10px 20px -12px rgba(0, 0, 0, 0.42), 0 3px 20px 0px rgba(0, 0, 0, 0.12), 0 8px 10px -5px rgba(0, 0, 0, 0.2)
  }


  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
    background: var(--color1);
  }

  img {
    height: 16rem;
    width: 16rem;
    border-radius: 3px;
    box-shadow: var(--shadow);
  }

  h1 {
    color: var(--color5);
    text-transform: uppercase;
    font-size: 2rem;
    font-weight: 100;
    line-height: 1.1;
    margin: 0.2rem auto;
    max-width: 14rem;
  }

  p {
    max-width: 14rem;
    margin: 1rem auto;
    line-height: 1.35;
  }

  @media (min-width: 480px) {
    h1 {
      max-width: none;
    }

    p {
      max-width: none;
    }
  }

  .navbar {
    width: auto;
    display: flex;
    align-items: center;
  }
  
  .navbar > * {
    margin: 8px 8px;
  }

  a {
    text-decoration-line: none;
    color: var(--color5);
  }

  .space {
    flex-grow: 4;
  }
  
</style>
