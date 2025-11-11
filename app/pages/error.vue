<script setup lang="ts">
const route = useRoute();
const error = route.query.error || "Something went wrong";
</script>

<template>
  <div class="card bg-base-300 container mt-4 text-center min-h-72 mx-auto flex flex-col justify-center items-center gap-4">
    <div role="alert" class="alert alert-error min-w-1/2 text-center">
      <span>Uh Ohh! {{ error }}. Please contact customer support</span>
    </div>

    <Nuxtlink to="/" class="btn btn-primary">
      <Icon name="tabler:arrow-left" size="32" />
      Home
    </Nuxtlink>
  </div>
</template>
