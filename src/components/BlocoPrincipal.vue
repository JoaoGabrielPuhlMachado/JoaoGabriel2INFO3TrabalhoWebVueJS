<script>
import MaisUm from "@/components/MaisUm.vue";
export default {
  components: { MaisUm },
};
</script>
<template>
  <main id="content">
    <MaisUm titulo="Bloco 1" :nomes="['Heloisa', 'Eduardo']" />
    <MaisUm titulo="URGENTE" class="alerta" :nomes="['Eduardo', 'Wedley']" />
    <MaisUm />
    <MaisUm class="alerta" />
    <MaisUm />
    <MaisUm />
  </main>
</template>
<style></style>
