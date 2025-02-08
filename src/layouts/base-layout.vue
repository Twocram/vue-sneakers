<script setup lang="ts">

</script>


<template>
    <div class="container">
        <div class="wrapper">
            <slot></slot>
        </div>
    </div>
</template>

<style scoped>
.container {
    padding: 85px;
    background-color: #E7F6FF;
    height: 100%;
}

.wrapper {
    background-color: #FFFFFF;
    border-radius: 20px;
    height: 100%;
}
</style>