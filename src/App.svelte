<script>
  import {fade} from 'svelte/transition';
  const message = 'Hello, my Svelte Snowpack world!!';
</script>

<style type="text/scss">
  @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');

  :global(html) {
    height: 100%;
  }

  :global(body) {
    margin: 0;
    font-family: 'IBM Plex Sans', sans-serif;
    min-height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: dodgerblue;
    color: white;
  }
</style>

<h1 transition:fade>{message}</h1>
