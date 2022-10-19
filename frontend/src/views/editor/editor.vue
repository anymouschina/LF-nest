<template>
  <div class="edit-wrapper">
    <div class="editor-container">
      <div class=" show-grid">

      </div>
    </div>
   
    <div>
      <DraggableBox></DraggableBox>
    </div>
  </div>
</template>

<script setup lang="ts">
import DraggableBox from './components/DraggableBox.vue'
</script>

<style lang="scss" scoped>

.edit-wrapper{
  display: flex;
  .editor-container{
  width:1024px;
  max-width: 1292px;
  height: 1024px;
}

}

.show-grid {
    width: 100%;
    max-width: 1292px;
    height: 2400px;
    position: absolute;
    background-size: 30.0465px 10px;
        outline: 1px dotted #4d72da;
        background-image: linear-gradient(to right,
            rgba(194, 191, 191, 0.2) 1px,
            transparent 1px),
          linear-gradient(to bottom,
            rgba(194, 191, 191, 0.2) 1px,
            transparent 1px);
      }
</style>