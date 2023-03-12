<template>
  <DefaultHeader></DefaultHeader>
  <DisplayList></DisplayList>
  <DefaultFooter></DefaultFooter>
</template>

<script>
import DefaultHeader from "./components/DefaultHeader.vue";
import DefaultFooter from "./components/DefaultFooter.vue";
import DisplayList from "./components/DisplayList.vue";

export default {
  name: "App",
  components: {
    DefaultHeader,
    DefaultFooter,
    DisplayList,
  },
};
</script>

<style>
/*#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
