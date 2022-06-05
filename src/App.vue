<template>
<div>
    <PDFView :pdfUrl="jsPdf" />
</div>
</template>
<script setup lang="ts">
import PDFView from "./components/pdfPreview.vue"
import jsPdf from "./Javascript.pdf"
</script>
