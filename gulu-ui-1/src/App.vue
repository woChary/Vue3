<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <div>导航栏
    <router-link to="/">f1</router-link>
    <router-link to="/xxx">f2</router-link>
  </div>
  <router-view/>
</template>

<script>

export default {
  name: 'App',
}
</script>
