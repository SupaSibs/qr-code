<script lang="ts">
import Card from "./lib/Card.svelte"
  import Attribution from "./lib/Attribution.svelte"
</script>

<div>
<Card />
</div>

<style lang="scss">
  @use "./styles/template" as template;
  div {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    flex-direction: column;
  background-color: template.$lG;
  }
</style>