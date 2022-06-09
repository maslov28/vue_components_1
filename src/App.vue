<template>
  <p>
    создать компонент, который принимает параметром строку и добавляет к ней текущую дату
  </p>
  <new-component date="Today: "></new-component>
</template>

<script>
import NewComponent from './components/NewComponent.vue'
export default {
  components: {NewComponent}
}
</script>

<style>

</style>
