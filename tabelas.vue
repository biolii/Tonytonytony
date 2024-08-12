<template>
    <div class="layout-tabela">
      <div class="tabelas">
        <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>Nome</th>
            <th>Telefone</th>
            <th>Email</th>
            <th>Data</th>
            <th>Endereço</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="(item, index) in tableData" :key="index">
            <td>{{ item.id }}</td>
            <td>{{ item.nome }}</td>
            <td>{{ item.telefone }}</td>
            <td>{{ item.email }}</td>
            <td>{{ item.data }}</td>
            <td>{{ item.endereco }}</td>
          </tr>
        </tbody>
      </table>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        tableData: [
          { id: "#0001", nome: "Tabala", telefone: "", email: "", data: "", endereco: "" },
          { id: "0002", nome: "bela", telefone: "", email: "", data: "", endereco: "" },
        ]
      };
    }
  };
  </script>
  
<style lang="scss">

@import '/assets/styles/theme.scss';

</style>