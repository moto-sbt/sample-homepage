<template>
  <b-navbar toggleable="lg" type="dark" variant="primary">
    <b-navbar-brand>
      <NuxtLink tag="div" to="/" class="c-p">Sample HomePage</NuxtLink>
    </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item>
          <NuxtLink tag="div" to="/gaiyou">会社概要</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink tag="div" to="/service">主要業務</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink tag="div" to="/performance">実績</NuxtLink>
        </b-nav-item>
        <b-nav-item>
          <NuxtLink tag="div" to="/inquiry">お問い合わせ</NuxtLink>
        </b-nav-item>
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
.c-p {
  cursor: pointer;
}
</style>