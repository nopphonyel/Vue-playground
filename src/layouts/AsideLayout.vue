<template>
  <v-layout class="rounded rounded-md">
    <v-navigation-drawer>
      <v-list>
        <v-list-item title="Navigation drawer"></v-list-item>
      </v-list>
    </v-navigation-drawer>

    <v-app-bar title="Application bar">
      <div class="px-2 mx-2">123</div>
      <div class="px-2 mx-2">123</div>
      <div class="px-2 mx-2">123</div>
      <div class="px-2 mx-2">123</div>
      <div class="px-2 mx-2">123</div>
      <div class="px-2 mx-2">123</div>
    </v-app-bar>

    <v-main class="d-flex align-center justify-center" style="min-height: 300px">
      <slot />
    </v-main>
  </v-layout>
</template>
