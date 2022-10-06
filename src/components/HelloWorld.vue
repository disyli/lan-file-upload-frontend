<script setup>
import { ref } from 'vue'

defineProps({
  msg: String
})
const uploadRef3 = ref();
const count = ref(0)
</script>

<template>
  <t-upload action="/api/upload"
                    allowUploadDuplicateFile
                    showUploadProgress
                    useMockProgress
                    autoUpload
                    multiple
                    theme="image" /></template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
