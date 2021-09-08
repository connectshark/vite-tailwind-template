<template>
  <h1 class="text-4xl text-gray-800 font-sans">{{title}}</h1>
  <router-view></router-view>
</template>

<script>
export default {
  setup () {
    return {
      title: 'Hello'
    }
  }
}
</script>


<style>
#app {
  font-family: 'openhuninn', 'Noto Sans TC', sans-serif;
  text-align: center;
}
</style>
