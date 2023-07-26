<script setup>
import {ref,reactive,computed} from 'vue'
const state=reactive({
    count:0
})
</script>
<template>
<div>
<button @click="state.count++" class="box bg-indigo-500 text-white hover:bg-gray-300 hover:text-slate-500 duration-150">+</button>
<span>{{state.count}}</span>
<button @click="state.count--" class="box bg-indigo-500 text-white hover:bg-gray-300 hover:text-slate-500 duration-150">-</button>
<a href="/" class="btn btn-outline btn-primary" >home</a>
</div>
</template>
<style scoped></style>