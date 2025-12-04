<script lang="ts" setup>
const props = defineProps<{
  label: string;
  icon: string;
  href: string;
}>();
</script>

<template>
  <NuxtLink :to="props.href" class="flex gap-2 justify-start p-2 hover:bg-base-300 cursor-pointer">
    <Icon :name="props.icon" size="24" />
    {{ props.label }}
  </NuxtLink>
</template>
