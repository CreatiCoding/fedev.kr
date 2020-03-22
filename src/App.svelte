<script>
  import Header from "./containers/Header.svelte";
  import Footer from "./containers/Footer.svelte";
  import LeftNav from "./containers/LeftNav.svelte";
  import RightNav from "./containers/RightNav.svelte";
  import Contents from "./containers/Contents.svelte";
</script>

<style>
  :global(body) {
    background-color: #fffaca;
    padding: 0;
    margin: 0;
  }
  :global(p),
  :global(span),
  :global(h1) {
    padding: 0;
    margin: 0;
  }
  .wrapper {
    max-width: 1080px;
    margin: 0 auto;
  }
</style>

<div class="app">
  <div class="wrapper">
    <Header />
    <LeftNav />
    <RightNav />
    <Contents />
    <Footer />
  </div>
</div>
