<template>
  <b-navbar toggleable="lg" type="dark" variant="primary">
    <b-navbar-brand href="#">Sample HomePage</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">会社概要</b-nav-item>
        <b-nav-item href="#">主要業務</b-nav-item>
        <b-nav-item href="#">実績</b-nav-item>
        <b-nav-item href="#">お問い合わせ</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
})
</script>

<style>

</style>