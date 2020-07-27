<template>
  <div id="app">
    <MyName name="Tobiloba Adegbaju"/>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
  }
}
</script>

<style>
@import url('https://cdn.rawgit.com/mfd/09b70eb47474836f25a21660282ce0fd/raw/e06a670afcb2b861ed2ac4a1ef752d062ef6b46b/Gilroy.css');

#app {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: 'Gilroy', sans-serif;
  font-size: 24px;
  color: #000;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
