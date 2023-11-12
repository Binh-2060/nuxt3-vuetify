<script lang="ts" setup></script>

<template>
  <v-app-bar density="comfortable" color="primary">
    <template v-slot:prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>

    <div>meeyoodee</div>

    <template v-slot:append>
      <AvatarMenu />
    </template>
  </v-app-bar>
</template>
