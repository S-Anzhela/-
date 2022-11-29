<template>
  <a href="#" class="btn btn-success" @click="DialogShow">Add product</a>
  <MyDialog v-model:show="DialogVisible">Content component</MyDialog>
  <homeTop/>
  <router-view/>
</template>


<script setup>
import {ref} from 'vue';
import homeTop from "@/components/templates/homeTop";

  
    const DialogVisible = ref(false);
    const DialogShow = () => {
      DialogVisible.value = true;
    };

</script>
