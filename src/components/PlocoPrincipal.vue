<script>
import ArtiGo from "@/components/ArtiGo.vue";
export default {
  components: { ArtiGo },
};
</script>
<template>
  <main id="content">
    <ArtiGo titulo="Bloco1" :nomes="['Heloisa', 'Rafaela']" />
    <ArtiGo titulo="URGENTE" class="alerta" :nomes="['ligia', 'joao']" />
    <ArtiGo />
    <ArtiGo class="alerta" />
    <ArtiGo />
    <ArtiGo />
  </main>
</template>
<style></style>
