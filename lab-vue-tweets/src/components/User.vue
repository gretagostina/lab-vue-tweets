<template>
    <span className="user">
        <span className="name">{{ props.user.name }}</span>
        <span className="handle">{{ props.user.handle }}</span>
    </span>
</template>

  <script setup>
const props = defineProps({
  user: Object,
});
</script>