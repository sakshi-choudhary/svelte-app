<script>
  let name = "Hey there";
  function fetchMe() {
    console.log("Hello world!");
  }
</script>
<main>
  <h1>{name}</h1>
  <button on:click={fetchMe}>Fetch Data!</button>
</main>
