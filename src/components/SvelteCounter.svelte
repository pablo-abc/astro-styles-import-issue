<script>
  let count = 0;

  function add() {
    count += 1;
  }

  function subtract() {
    count -= 1;
  }
</script>

<div id="svelte" class="counter">
  <button on:click={subtract}>-</button>
  <pre>{ count }</pre>
  <button on:click={add}>+</button>
</div>

<style>
  .counter {
    color: #333;
    background: pink;
  }
</style>
