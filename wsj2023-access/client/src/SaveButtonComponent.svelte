<script>
    export let key;
    export let row;
    export let col;
    export let onSaveButtonClick;
  </script>

  <button on:click={() => onSaveButtonClick(row)}
    >{key}
  </button>