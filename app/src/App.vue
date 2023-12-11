<script setup>
import Card from './components/Card.vue'
</script>
<template>
  <div class="card__title">Заголовок в app</div>
  <Card title="Рубашка 1" :price="30000">
    <button>Жмакни</button>
  </Card>
  <Card title="Рубашка 2" :price="31000 + 500" is-added="true" />
  <Card title="Рубашка 3" price="32 000 + 500" :isAdded="true" />
  <Card title="Рубашка 4" price="33 000" />
  <Card title="Рубашка 5" price="34 000" />
</template>
<style>
body {
  background-color: black;
  color: white;
}
</style>
