<template>
  <section class="score">
    Jogador <span>{{ win_count }}</span> x
    <span>{{ lose_count }}</span> Computador
  </section>
</template>
<script>
export default {
  props: ['win_count', 'lose_count'],
};
</script>

<style scoped>
section.score {
  border-bottom: 1px solid black;
  padding: 24px;
  font-size: 18px;
}
span {
  padding: 8px;
  font-weight: bold;
  border: 1px solid black;
}
</style>
