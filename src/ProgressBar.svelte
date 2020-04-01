<script>
  export let progress = 0;
</script>

<style>
  .progress-container {
    margin: 20px 0;
    border: solid rgb(194, 194, 194) 1px;
  }
  .progress-bar {
    height: 30px;
    background-color: rgb(77, 199, 55);
  }
</style>

<div bp="grid">
  <div bp="offset-5@md 4@md 12@sm" class="progress-container">
    <div class="progress-bar" style="width: {progress}%;">
      <span class="sr-only">%{progress}</span>
    </div>
  </div>
</div>
