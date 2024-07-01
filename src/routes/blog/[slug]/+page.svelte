<script lang="ts">
    export let data;
</script>

<div>
  {#each data.names as { name }}
    <div class="font-bold text-sky-400">{name}</div>
  {/each}
</div>