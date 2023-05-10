<script>
import Cards from './Cards.vue';
export default {
  name: 'Main',

  components:{
    Cards,
  }

}
</script>

<template> 
<main>
    <Cards />
</main>
</template>

<style lang="scss" scoped>
@use '../scss/partials/generals' as *;
@use '../scss/partials/variables' as *;

main{
  background-color: $bg-orange;
}
</style>