<template>
  <div class="container">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: 'custom-container',
};
</script>

<style>

.container {
  max-width: 1376px;
  margin: 0 auto;
  padding: 0 40px;
}

@media (max-width: 768px) {
  .container {
    padding: 0 15px;
  }
}
</style>
