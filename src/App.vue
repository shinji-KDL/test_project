<template>
  <div id="app">  
    <div class="wrapper">
      <MyHeader></MyHeader>
      <MyAside></MyAside>
      <div class="content-wrapper"></div>
       <router-view/>
    </div>
    </div>
  </div>
</template>

<script>
import MyHeader from "@/components/MyHeader";
import MyAside from "@/components/MyAside";
export default {
  name: "app",
  components: {
    MyHeader,
    MyAside
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
