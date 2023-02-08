<template>
  <q-layout>
    <q-header class="bg-teal">
      <q-toolbar>

        <q-toolbar-title> Ev Charge Map </q-toolbar-title>

        <q-btn flat round dense icon="login" />

      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated>
      <q-tabs class="text-light bg-teal">
        <q-tab name="/map" label="Map" icon="explore" />
        <q-tab name="/route" label="Routes" icon="directions" />
        <q-tab name="/auth" label="Auth" icon="login" />
      </q-tabs>
    </q-footer>
  </q-layout>
</template>

<script setup>

</script>
