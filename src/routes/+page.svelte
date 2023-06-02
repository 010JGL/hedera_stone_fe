<script lang="ts">
  export let data;
</script>

<h1>Welcome to Hedera stone</h1>

<div>
{#each data.cart as { id, quantity } (id)}
  <div>{id} - {quantity}</div>
{/each}
</div>
