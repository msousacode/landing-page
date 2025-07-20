<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-white text-primary">
      <div class="row justify-center q-pa-md">
        <q-btn flat no-caps label="Sobre Nós" size="17px"></q-btn>
        <q-btn flat no-caps label="Planos" size="17px"></q-btn>
        <q-btn flat no-caps label="Perguntas Frequentes" size="17px"></q-btn>
      </div>
    </q-header>

    <q-page-container>
      <IndexPage />
    </q-page-container>

    <q-footer class="text-center bg-white text-primary">
      <div class="row justify-center q-pa-md">
        <span class="text-caption"> © 2024 Vamos ver. Todos os direitos reservados. </span>
      </div>
    </q-footer>
  </q-layout>
</template>

<script setup lang="ts">
import IndexPage from 'src/pages/IndexPage.vue';
</script>
