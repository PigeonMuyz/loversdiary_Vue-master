<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" v-if="false"/> -->
  <diaryCompent v-if="true"/>
  <!-- <var-button>111</var-button> -->
  <var-bottom-navigation v-model:active="active" fixed="true" safe-area="true" border="true">
    <var-bottom-navigation-item label="友人记"/>
    <var-bottom-navigation-item label="关于"/>
  </var-bottom-navigation>
</template>

<script>
import diaryCompent from './components/diary.vue'
export default {
  name: 'App',
  components: {
    diaryCompent
  },
  data(){
    return{
      active: 0
    }
  }
}
</script>

<style>

</style>
