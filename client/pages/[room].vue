<script lang="ts" setup>
const route = useRoute()
const room = route.params.room
</script>

<template>
    <div>hello welcome to something {{ room }}</div>
</template>
