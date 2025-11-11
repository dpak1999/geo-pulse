<template>
  <div class="navbar bg-primary text-primary-content">
    <div class="navbar-start">
      <NuxtLink to="/" class="btn-ghost text-xl">
        Geopulse
      </NuxtLink>
    </div>
    <div class="navbar-end">
      <app-theme-toggle />
      <AuthButton />
    </div>
  </div>
</template>
