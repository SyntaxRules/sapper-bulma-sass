<script>
  import Nav from "../components/Nav.svelte";

  export let segment;
</script>

<style lang="scss">
  :global {
    @import "./style/global.scss";
  }
  main {
    background-color: white;
  }
</style>

<Nav {segment} />

<main class="container">
  <slot />
</main>
