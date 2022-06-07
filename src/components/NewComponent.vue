<template>
  <span>{{combineStrings}}</span>
</template>

<script>
export default {
  props: ['date'],
  computed: {
    combineStrings() {
      return this.date + new Date().toLocaleDateString()
    }
  }

}
</script>

<style>

</style>