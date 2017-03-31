<template>
  <q-layout>
    <div slot="header" class="toolbar">
      <q-toolbar-title :padding="0">
        Quasar Framework v{{$q.version}}
      </q-toolbar-title>
    </div>

    <!--
      Replace following "div" with
      "<router-view class="layout-view">" component
      if using subRoutes
    -->
    <div class="layout-view">
      <h1>Olá, Bem vindo ao app do curso Iniciando com Quasar Framework</h1>
      <p>Veja os últimos repositórios do Erik</p>

      <button class="primary" v-link="'/repos'">ver</button>
    </div>
  </q-layout>
</template>

<script>
export default {}
</script>

<style lang="styl">

</style>
