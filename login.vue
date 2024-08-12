<template>
    <div class="default-layout">
        <div class="login-container" >
            <p class="p-login" >Acessar o sistema</p>
            <input class="text-input" type="text" name="name" id="name" placeholder="Usuário">
            <input class="text-input" type="password" name="password" id="password" placeholder="Senha">
            <nuxt-link to="/">
                <button class="btn-primary">Entrar</button>
            </nuxt-link>
            <p class="p-login" >ou</p>
            <button class="btn-primary">Entre com <strong>gov.br</strong></button>
        </div>
    </div>
  </template>

<style lang="scss">

@import '/assets/styles/theme.scss';

</style>