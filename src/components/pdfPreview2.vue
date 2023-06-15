<template>
    <vue-pdf-app theme="dark" class="pdf" pdf="http://storage.xuetangx.com/public_assets/xuetangx/PDF/PlayerAPI_v1.0.6.pdf"></vue-pdf-app>
</template>
<script lang="ts" setup>
import { ref } from "vue";
import VuePdfApp from "vue3-pdf-app";
import "vue3-pdf-app/dist/icons/main.css";
    
</script>
<style >
.pdf{
    height: 300px;
}
</style>