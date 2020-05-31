<template>
  <header>
    <div class="header">
      <div class="my-auto">
        <router-link class="d-inline" to="/">
          <img class="logo-big" src="../images/logo.svg" />
        </router-link>
      </div>
      <div class="break"></div>
      <div class="my-auto">
        <h2>
          <router-link to="/what">What</router-link>
        </h2>
      </div>
      <div class="my-auto">
        <h2>
          <router-link to="/who">Who</router-link>
        </h2>
      </div>
      <div class="my-auto">
        <h2>
          <router-link to="/where">Where</router-link>
        </h2>
      </div>
    </div>
  </header>
</template>
<script>
export default {
  name: "MyHeader"
};
</script>
