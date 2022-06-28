<script>
  import Navbutton from "./navbutton.svelte";
</script>

<nav>
  <img src="/logo.svg" alt="Minocto logo" />
  <h1>Minocto</h1>
  <div class="grow" />
  <Navbutton name="Home" loc="/" />
  <Navbutton name="Products" loc="/products" />
  <Navbutton name="GitHub" loc="https://github.com/minocto" />
</nav>

<style lang="scss">
  nav {
    height: $nav-height;
    display: flex;
    flex-direction: row;
    align-items: center;
    background-color: $col-bg-light;

    img {
      width: 2rem;
      height: 2rem;
    }

    h1 {
      margin-left: 0.5rem;
      font-size: 1.75rem;
    }
  }

  @media only screen and (min-width: 768px) {
    nav {
      padding: 0 20%;
    }
  }
</style>
