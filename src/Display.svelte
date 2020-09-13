<script>
  import { primary } from "./store";

  let secondary = "500 + 12 * 20";
</script>

<style>
  .display-border {
    margin: 20px;
    border-radius: 8px;
    background: #e5e5e5;
    border: 1px solid #e5e5e5;
    background: linear-gradient(45deg, #cbd4c4, #acba9e);
    box-shadow: inset 4px 4px 7px #8a9580, 9px 9px 27px #c5c5c5,
      -9px -9px 27px #ffffff;
  }
  .display {
    padding: 10px 20px;
  }
  h1 {
    text-align: right;
    margin: 1vh;
    font-size: 6vh;
  }
  h3 {
    text-align: right;
    margin: 1vh;
    font-size: 3vh;
  }
</style>

<div class="display-border">
  <div class="display">
    <h3>{secondary}</h3>
    <h1 placeholder="0">{$primary}</h1>
  </div>
</div>
