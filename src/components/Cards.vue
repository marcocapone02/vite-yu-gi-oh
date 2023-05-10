<script>
export default {
  name: 'Cards'
}
</script>

<template>

  <div class="container">

    <div class="card">
      <img src="https://images.ygoprodeck.com/images/cards/34541863.jpg" alt="">
      <h3>"A" Cell Breeding Device</h3>
      <p>Spell Card</p>
    </div>

    <div class="card">
      <img src="https://images.ygoprodeck.com/images/cards/34541863.jpg" alt="">
      <h3>"A" Cell Breeding Device</h3>
      <p>Spell Card</p>
    </div>

    <div class="card">
      <img src="https://images.ygoprodeck.com/images/cards/34541863.jpg" alt="">
      <h3>"A" Cell Breeding Device</h3>
      <p>Spell Card</p>
    </div>
    
    <div class="card">
      <img src="https://images.ygoprodeck.com/images/cards/34541863.jpg" alt="">
      <h3>"A" Cell Breeding Device</h3>
      <p>Spell Card</p>
    </div>

    <div class="card">
      <img src="https://images.ygoprodeck.com/images/cards/34541863.jpg" alt="">
      <h3>"A" Cell Breeding Device</h3>
      <p>Spell Card</p>
    </div>

  </div>

</template>

<style lang="scss" scoped>
@use '../scss/partials/generals' as *;
@use '../scss/partials/variables' as *;

.container{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 30px;
  background-color: white;
}

.card{
  margin-bottom: 15px;
  height: 380px;
  width: 170px;
  text-align: center;
  background-color: $bg-orange;

  h3{
    color: white;
  }
  
  img{
    height: 250px;
  }
  
  p{
    padding: 36px;
  }
}
</style>