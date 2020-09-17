<template>
  <div class="feed-the-cat">
      <span class="header-text">Ты сегодня покормил кота?</span>
      <div class="container-box">
        <BoxDefault />
        <BoxDefault />
        <BoxDefault />
      </div>
  </div>
</template>

<script>
import BoxDefault from './BoxDefault.vue'

export default {
  name: 'Main',
  components: {
    BoxDefault
  }
}
</script>

<style>

.feed-the-cat {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
    background: url('../../assets/background.jpg') no-repeat;
    background-size: 100%;
}

.header-text {
    font-family: 'Exo20';
    font-size: 54px;
    color: #fff;
    margin-bottom: 45px;
}

.container-box {
    display: flex;
    justify-content: space-between;
    width: 90%;
    height: 70%;
    margin: 0 auto;
}

</style>