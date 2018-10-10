<template>
  <div>
    <p class="testButton">
      {{text}}
      
    </p>
    <vbutton>yeah</vbutton>
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
