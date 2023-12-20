<template>
    <div class="container">Home</div>
</template>

<script setup>
import {ref,onMounted} from 'vue'
const count = ref(0);
onMounted(()=>{
    console.log(count.value);
})
</script>

<style scoped>
.container {
    width: 100vw;
    height: 100vh;
}
</style>