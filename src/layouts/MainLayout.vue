<template>
  <q-layout view="lHr lpR lfr">
    <q-header class="header">
      <q-toolbar>
        <q-toolbar-title>UAS-Lab Ahmad Fadil</q-toolbar-title>
        <q-tabs align="left">
          <q-route-tab to="/" label="Weather" />
        </q-tabs>
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
    <q-footer class="footer">
      <q-toolbar>
        <q-toolbar-title>
          Copyright © 2022 Ahmad Fadil.®. All rights reserved.
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>

<script setup></script>

<style>
.header {
  background: linear-gradient(to right, #ff7e5f, #feb47b); /* Gradient */
  color: #fff;
}

.footer {
  background: linear-gradient(to right, #ff7e5f, #feb47b); /* Gradient */
  color: #fff;
}

.q-toolbar {
  padding: 0 30px !important;
}

.q-toolbar__title:first-child {
  padding-left: 20px !important;
}

.q-tab {
  padding: 0 15px !important;
  min-height: 50px !important;
  color: #fff !important;
}

.q-tab--active {
  color: #ff7e5f !important; /* Active tab color */
}
</style>
