<template>
    <img :src="props.user.image" className="profile" alt="profile"/>
</template>

<script setup>
    const props = defineProps({
      user: Object,
    });
</script>