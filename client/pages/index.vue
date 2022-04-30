<script lang="ts" setup>
const variable = ref("shekhar")
</script>

<template>
    <div class="welcome" @click="variable += 'a'">
        hello welcome, {{ variable }}
    </div>
</template>

<style>
.welcome {
    background-color: red;
}
</style>
