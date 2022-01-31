<template>
  <div>
    <h1>お問い合わせ</h1>
    <button @click="buttonClick">app</button>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  methods: {
    buttonClick(): void {
      console.log("test")
    }
  }
})
</script>

<style>

</style>