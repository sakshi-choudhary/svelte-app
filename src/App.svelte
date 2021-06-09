<script>
  let name = "Hey there";
  function fetchMe() {
    console.log("Hello world!");
  }

  let count = 0;
  const counter = () => {
    count++;
  };

</script>

<main>
  <h1>{name}</h1>
  <button on:click={fetchMe}>Fetch Data!</button>
  <button on:click={counter}>counter</button>
  <h2>{count}</h2>
</main>
