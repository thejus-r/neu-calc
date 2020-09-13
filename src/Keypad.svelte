<script>
  import Key from "./key.svelte";
</script>

<style>
  .key-container {
    width: fit-content;
    padding: 15px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    grid-gap: 2vh 2vh;
  }
</style>

<div class="key-container">
  <Key keyValue="AC" />
  <Key keyValue="Del" />
  <Key keyValue="%" />
  <Key keyValue="/" />
  <Key keyValue="7" />
  <Key keyValue="8" />
  <Key keyValue="9" />
  <Key keyValue="X" />
  <Key keyValue="4" />
  <Key keyValue="5" />
  <Key keyValue="6" />
  <Key keyValue="-" />
  <Key keyValue="1" />
  <Key keyValue="2" />
  <Key keyValue="3" />
  <Key keyValue="+" />
  <Key keyValue="." />
  <Key keyValue="0" />
  <Key keyValue="()" />
  <Key keyValue="=" />
</div>
