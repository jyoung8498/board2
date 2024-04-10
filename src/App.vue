  <template>
    <div id="app">
        <appHeader></appHeader>
        <CustomComponent></CustomComponent>
        <appFooter></appFooter>
    </div>
  </template>

<script setup>
    import appHeader from './components/appHeader.vue';
    import CustomComponent from './components/tableCon.vue';
    import appFooter from './components/appFooter.vue';
    
</script>

<style>
  html, body {font-size:16px;}
</style>