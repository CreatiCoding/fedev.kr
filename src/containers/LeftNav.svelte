<script>
  function goReactSite() {
    window.location.href = "//react.fedev.kr";
  }
  function goHome() {
    window.location.href = "/";
  }
</script>

<style>
  .left-nav {
    float: left;
    width: 200px;
    max-width: 200px;
    overflow: hidden;
    padding: 20px;
    padding-top: 0;
  }
  .container {
    padding: 10px;
  }
  .menu {
    text-align: center;
    width: 100%;
    height: 50px;
    font-size: 2rem;
    cursor: pointer;
  }
  .text {
    display: inline;
    vertical-align: middle;
  }
  .react {
    color: #60dafb;
    background: black;
    font-weight: bold;
  }
  .vuejs {
    color: #42b883;
    background: #35495d;
    font-weight: bold;
  }
  .angular {
    color: #ffffff;
    background: #c3002f;
    font-weight: bold;
  }
  .svelte {
    color: #ff3d00;
    background: #ffffff;
    font-weight: bold;
    /* outline: 2px solid; */
    /* margin: 2px; */
  }
</style>

<div class="left-nav">
  <div class="container">
    <div class="menu react" on:click={goReactSite}>
      <div class="text">react</div>
    </div>
    <div class="menu svelte" on:click={goHome}>
      <div class="text">svelte</div>
    </div>
    <div class="menu vuejs">
      <div class="text">vuejs</div>
    </div>
    <div class="menu angular">
      <div class="text">angular</div>
    </div>
  </div>
</div>
