<template>
    <InputComponent id="id" name="id" type="hidden"/>
    <ImputComponent id="Primer nombre" name="Primer nombre"  placeholder="Primer nombre:"></ImputComponent>
    <ImputComponent id="segundo nombre" name="segundo nombre"  placeholder="segundo nombre:"></ImputComponent>
    <ImputComponent id="Primer apellido" name="Primer apellido"  placeholder="Primer apellido:"></ImputComponent>
    <ImputComponent id="segundo Apellido" name="segundo Apellido"  placeholder="segundo Apellido:"></ImputComponent>    
    <ImputComponent id="Tip Documento" name="Tip Documento"  type="Tip Documento"placeholder="Tip Documento"></ImputComponent>
    <ImputComponent id="Documento" name="Documento"  type="Documento"placeholder="Documento"></ImputComponent>
</template>
<script setup lang="ts">

import ImputComponent from '@/components/ImputComponent.vue';

</script>
