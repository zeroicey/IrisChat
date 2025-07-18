<template>
<h1>hello,this is home page</h1>
<div>fasjfkajfkasjfkasfj</div>
<button @click="tocommunity">跳</button>
</template>

<script setup>
import {ref} from "vue"
import { RouterView } from "vue-router";
import router from "../router";


const tocommunity= ()=> {
    router.push('/community')
}
</script>

<style>
* {
    padding: 0;
    margin: 0;
}
</style>