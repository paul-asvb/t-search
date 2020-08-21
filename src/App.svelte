<script>
  import "smelte/src/tailwind.css";
  import TextField from "smelte/src/components/TextField";
  import Button from "smelte/src/components/Button";
  import ProgressCircular from "smelte/src/components/ProgressCircular";

  function handleClick() {
    console.log("test");
  }
</script>

<main>
  <h4 class="h4">123Karl Search</h4>
  <TextField class="col-span-3 ..." label="Type a movie and a year: " />
  <Button on:click={handleClick}>Search</Button>
  <ProgressCircular />
</main>
