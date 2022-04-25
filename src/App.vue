<script>
import MenuLateral from "@/components/MenuLateral.vue";
import BlocoPrincipal from "@/components/BlocoPrincipal.vue";
import CabecaAlho from "@/components/CabecaAlho.vue";
import FooterBol from "@/components/FooterBol.vue";

export default {
  components: { MenuLateral, BlocoPrincipal, CabecaAlho, FooterBol },
};
</script>
<template>
  <CabecaAlho />
  <MenuLateral />
  <BlocoPrincipal />
  <FooterBol />
</template>
<style></style>
