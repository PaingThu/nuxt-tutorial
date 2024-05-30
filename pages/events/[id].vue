<script setup>
    const route = useRoute();
    console.log("Route ", route.params.id)
</script>
<template>
    <div>
        Event Id: {{ $route.params.id }}
    </div>
</template>