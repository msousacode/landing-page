<template>
  <q-layout view="lHh Lpr lFf">
    <q-header>
      <div class="row justify-center q-pa-md shadow-4">
        <q-btn flat no-caps label="Sobre Nós" size="17px"></q-btn>
        <q-btn flat no-caps label="Planos" size="17px"></q-btn>
        <q-btn flat no-caps label="Perguntas Frequentes" size="17px"></q-btn>
      </div>
    </q-header>

    <q-page-container>
      <IndexPage />
    </q-page-container>
  </q-layout>
</template>

<script setup lang="ts">
import IndexPage from 'src/pages/IndexPage.vue';
</script>
