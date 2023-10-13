<script setup lang="ts"></script>

<template>
    <div class="hightlighted">
        <ContentSlot :use="$slots.default" unwrap="pre" />
    </div>
</template>

<style scoped>
.hightlighted {
    color: var(--color-blue-500);
    font-size: 1.5rem;
}
</style>
