<script>
  import Container from "./container/container.svelte"
  import ContainerAdvertising from "./container/container-advertising.svelte"
</script>

<style>
  .content {
    margin-top: 25px;
    display: flex;
    align-items: flex-start;
  }
  .main {
    margin-right: 10px;
    flex: 2;
  }
  .advertising {
    font-weight: bold;
    text-align: center;
    display: flex;
    flex-direction: column;
    flex: 1;
  }
</style>

<div>
  <div class="content">
    <div class="main">
      <Container />
    </div>
    <div class="advertising">
      <ContainerAdvertising />
    </div>
  </div>
</div>
