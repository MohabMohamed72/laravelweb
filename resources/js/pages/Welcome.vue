<script setup lang="ts">
    fetch('/api/hello')
        .then(response => response.json())
        .then(data => {
            console.log(data);
        })
        .catch(error => {
            console.error('Error fetching data:', error);
        })
</script>
<template>
    <p>aaaaaa</p>
</template>