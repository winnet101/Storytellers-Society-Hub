<script>
  import { onMount } from "svelte";
  import Header from "./lib/Header.svelte";
  import { hash } from "./stores";
  import NotFound from "./lib/NotFound.svelte";
  import Home from "./lib/Home.svelte";
  import Board from "./lib/Board.svelte";

  onMount(() => {
    console.log("Page mounted!")
    function setHash() {
      hash.set(window.location.hash);
    }

    window.addEventListener("hashchange", () => {
      setHash();
    })

    return (() => {
      window.removeEventListener("hashchange", setHash);
    })
  })
</script>

<Header />

{#if $hash == ""}
  <Home />
{:else if $hash == "#board"}
  <Board />
{:else}
  <NotFound />
{/if}