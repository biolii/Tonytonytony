<template>
    <div class="default-layout">
      <form class="grid-layout" action="">
        <div class="input-container grid-item1">
          <input class="text-input " type="text" id="name" placeholder="Nome">
        </div>
        <div class="input-container grid-item2 ">
          <input class="text-input" type="email" id="Email" placeholder="E-mail">
        </div>
        <div class="input-container grid-item3">
          <input class="text-input" type="date" id="Datanasc" placeholder="Data de Nascimento" onfocus="(this.type='date')" onblur="if(this.value==''){this.type='text'}">
        </div>
        <div class="input-container grid-item4">
          <input class="text-input" type="tel" id="Tel" placeholder="Telefone">
        </div>
        <div class="input-container grid-item5">
          <input class="text-input" type="text" id="Endereco" placeholder="Endereço">
        </div>
        <div class="input-container grid-item6">
          <textarea class="textarea" name="Observações" id="Obs" cols="30" rows="10" placeholder="Digite sua mensagem:"></textarea>
        </div>
        <button class="btn-primary" type="submit">Enviar</button>
      </form> 
    </div>
  </template>
  
<style lang="scss">
  
  @import '/assets/styles/theme.scss';
  
</style>

