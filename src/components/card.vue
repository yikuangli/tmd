<template>
  <div>
    <p class="card">
      {{text}}
      {{t}}
    </p>
  </div>
</template>

<script>
export default {
  props: ['text']
}
</script>

<style>
.card {
  padding: 10px;
}
</style>
