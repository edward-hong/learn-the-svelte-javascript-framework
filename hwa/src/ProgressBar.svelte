<script>
  export let progress = 0
</script>

<div bp="grid">
  <div class="progress-container" bp="offset-5@md 4@md 12@sm">
    <div class="progress-bar" style="width: {progress}%;">
      <span class="sr-only">%{progress}</span>
    </div>
  </div>
</div>

<style>
  .progress-container {
    margin: 20px 0;
    border: 1px solid rgb(194, 194, 194);
  }

  .progress-bar {
    height: 30px;
    background-color: rgb(77, 199, 55);
  }
</style>