<template>
  <div class="main-home">
    <CardHome></CardHome>
    <MyHomeTable></MyHomeTable>
  </div>
</template>

<script>
import CardHome from '@/components/CardHome.vue';
import MyHomeTable from '@/components/MyHomeTable.vue';

export default {
  name: 'QRView',
  components:{
    CardHome,
    MyHomeTable
  }
}
</script>

<style scoped>
@import url('../styles.css');

.main-home{
  padding: 20px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}


</style>