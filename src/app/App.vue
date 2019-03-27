<template>
  <div id="app">
      <header>OK App</header>
    
        <ModalComponent />
        <TableComponent />
  
  </div>
</template>



<script>
import ModalComponent from './components/ModalComponent.vue';
import TableComponent from './components/TableComponent.vue';

export default {
  name: 'App',
  components: {
    ModalComponent,
    TableComponent
  }
}
</script>



<style lang="scss">

  html, body {
    height: 100%;
  }

  #app {
    height: inherit;
    background: white;
    display: flex;
    flex-direction: column;
    align-items: center;
    -webkit-align-items: center;
    justify-content: center;
    -webkit-justify-content: center;
  }

  .layout {
    
  }

</style>
