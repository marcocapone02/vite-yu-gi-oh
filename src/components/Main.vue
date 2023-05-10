<script>
import Cards from './Cards.vue'
import { store } from '../data/store'
export default {
  name: 'Main',
  components:{
    Cards,
  },

  data(){
    return{
      store
    }
  }

}
</script>

<template>

  <main>

    <div class="container">
      <Cards 
      v-for="card in store.cardsList"
      :key="card.id"
      :card="card"
      />
    </div>
    <br>
  </main>
</template>

<style lang="scss" scoped>
@use '../scss/partials/generals' as *;
@use '../scss/partials/variables' as *;

main{
  background-color: $bg-orange;
}
.container{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 50px;
  background-color: white;
}

</style>