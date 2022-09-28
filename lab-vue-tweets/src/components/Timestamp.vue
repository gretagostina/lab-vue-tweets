<template>
    <span className="timestamp">{{ props.timestamp }}</span>
</template>

<script setup>
    const props = defineProps({
      timestamp: String,
    });
</script>