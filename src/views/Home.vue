<template>
  <div class="home">
    <player></player>
  </div>
</template>

<script>
  import player from '../components/player.vue'
  export default{
    components:{
      player
    }
  }
</script>

<style scoped="scoped">
  .home {
    margin-top: 30vh;
    position: relative;
    z-index: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }

</style>
