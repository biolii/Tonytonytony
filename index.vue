<script setup lang="ts">

const inputPesquisa = ref(null);


const buscar = () => {
  console.log("Buscando:", inputPesquisa.value);
};

const onEnter = (event: KeyboardEvent) => {
  if (event.key === 'Enter') {
    buscar();
  }
};


</script>

<template>
    <div class="default-layout">
      <div class="input-container">
        <i class="pi pi-search icon"></i>
        <input class="text-input" type="text" name="text" id="text" placeholder="Busque por Nome ou CPF" v-model="inputPesquisa">
      </div>
      <br>
      <button class="btn-primary">Buscar</button>
      
    </div>
</template>

<style lang="scss">

@import '/assets/styles/theme.scss';

</style>
