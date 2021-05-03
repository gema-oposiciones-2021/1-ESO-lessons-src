<template>
  <div id="app">
    <mt-admin
      logoStr="OPOSICIONES 2021"
      :headImg="$store.state.headImg" 
      :headBg="$store.state.headBg"
      :menuData="$store.state.menuData" 
      userName="Gema Ester Pérez Ladera"
      :title="$route.name"
    ></mt-admin>
  </div>
</template>

<script>
  export default {
    name: 'app'
  }
</script>