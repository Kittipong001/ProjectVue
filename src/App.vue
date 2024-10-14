<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <q-layout view="hHh lpR fFf">

    <q-header elevated class="bg-primary text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title>
          My App
        </q-toolbar-title>
      </q-toolbar>

      <q-tabs>
        <q-route-tab to="/" label="Home" />
        <q-route-tab to="/Create" label="Create" />
        <q-route-tab to="/About" label="About" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>
