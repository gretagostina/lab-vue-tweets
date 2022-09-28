<template>
    <p className="message">{{ props.message }}</p>
</template>

<script setup>
    const props = defineProps({
      message: String,
    });
</script>