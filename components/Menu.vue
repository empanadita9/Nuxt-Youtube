<template>
  <div class="container mx-auto bg-white shadow-md py-1">
    <div class="grid grid-cols-12 gap-4">
      <div class="bg-red-200 col-span-3"><Logo /></div>
      <div class="bg-red-300 col-span-6">MI BSUCADOR</div>
      <div class="bg-red-400 col-span-3">LISTA DE OPCIONES</div>
    </div>
  </div>
</template>
<script>
import Logo from "@/components/menu/Logo.vue";
export default {
    components: {
        Logo
    }
}
</script>