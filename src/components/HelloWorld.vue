<script>
import {
    ref,
    reactive
} from 'vue'

const Data = reactive({
    number: 0,
    title: "This is title"
})
</script>

<template>
<h1>counter: {{ Data.counter }}</h1>
</template>

<style scoped>
</style>
