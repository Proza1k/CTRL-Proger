<script>
  import Logo from "./logo/logo.svelte";
  import Search from "./search/search.svelte";
  import Account from "./account/account.svelte";
</script>

<style>
  .header {
    font-family: "Roboto", sans-serif;
    width: 100%;
    height: 100px;
    border: 1px solid;
    border-radius: 20px;
    background-color: greenyellow;
    display: flex;
    align-items: center;
  }
</style>

<div class="header">
  <Logo />
  <Search />
  <Account />
</div>
