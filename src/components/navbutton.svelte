<script lang="ts">
  export var name: string;
  export var loc: string;
</script>

<a href={loc}>
  <button>{name}</button>
</a>

<style lang="scss">
  button {
    height: $nav-height;
    padding: 0.5rem;
    margin-left: 0.5rem;
    border: none;
    color: $col-fg;
    background-color: $col-bg-light;

    &:hover {
      background-color: $col-bg-lighter;
      cursor: pointer;
    }

    &:active {
      background-color: $col-bg-light;
    }
  }
</style>
