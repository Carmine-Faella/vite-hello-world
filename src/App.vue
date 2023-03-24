<script>
 import AppTitle from './components/AppTitle.vue';
 import AppHero from './components/AppHero.vue';

 export default {
  components:{
    AppTitle,
    AppHero,
  }
 }
</script>

<template>
    <AppTitle/>
    <AppHero/>
    <div>
      <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Reiciendis asperiores et repellendus nisi hic iste quibusdam autem eveniet voluptate. Consequatur assumenda illo a repellendus quibusdam ullam amet, corporis ad incidunt?</p>
      <button>Posti Vip</button>
    </div>
</template>

<style scoped>
  p{
    margin-top: 50px;
  }

  button{
    padding: 20px;
    width: 200px;
    border-radius: 20px;
    margin-top: 50px;
  }
</style>
