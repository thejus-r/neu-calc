<script>
  export let keyValue = "0";
  import { primary } from "./store";

  function handleClick() {
    $primary = $primary.concat(keyValue);
    console.log(keyValue, $primary);
  }
</script>

<style>
  .btn-container {
    width: 20%;
    height: 10vh;
    margin: 0px;
  }

  button {
    width: 100%;
    height: 100%;
    border-radius: 8px;
    border: none;
    outline: none;
    border-radius: 26px;
    border: 1px solid #e5e5e5;
    background: linear-gradient(145deg, #f5f5f5, #cecece);
    box-shadow: 8px 8px 11px #cecece, -8px -8px 11px #fcfcfc;
    transition: all 100ms ease-in-out;
    font-size: 4vh;
    font-weight: 600;
  }

  button:active {
    border-radius: 8px;
    background: linear-gradient(145deg, #cecece, #f5f5f5);
    box-shadow: 5px 5px 10px #cecece, -5px -5px 10px #fcfcfc;
  }
</style>

<div class="btn-container" on:click={handleClick}>
  <button>{keyValue}</button>
</div>
