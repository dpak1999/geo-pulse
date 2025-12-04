<template>
  <div class="flex-1 flex">
    <div class="bg-base-200 w-64">
      <div class="flex justify-end ">
        <Icon name="tabler:chevron-left" size="42" />
      </div>

      <div class="flex flex-col gap-2">
        <SidebarButton label="Locations" icon="tabler:map" href="/dashboard" />
        <SidebarButton
          label="Add location"
          icon="tabler:circle-plus-filled"
          href="/dashboard/add"
        />

        <div class="divider" />

        <SidebarButton
          label="Sign out"
          icon="tabler:logout-2"
          href="/sign-out"
        />
      </div>
    </div>

    <div class="flex-1" />
  </div>
</template>
