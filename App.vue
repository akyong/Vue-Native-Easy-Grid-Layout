<template>
   <Header />
    
</template>


<style>
/* 00ADE7 */
 @import "./sadis_component/css/style.css";

</style>

<script>

import Vue from "vue-native-core";
import { VueNativeBase } from "native-base";
import Header from "./sadis_component/Header.vue"
Vue.use(VueNativeBase);

// import {
//   createAppContainer,
//   createStackNavigator,
//   createDrawerNavigator
// } from "vue-native-router";

// import Heeader from "./sadis_component/header.vue";


// const DrawerNavigator = createDrawerNavigator(
//   {
//     Home: Header
//   },
//   {
//     initialRouteName: 'Home'
//   }
// );
// const StackNavigator = createStackNavigator(
//   {
//     Drawer: DrawerNavigator,
//     Home: HomeScreen,
//     Details: DetailsScreen
//   }
// );
// const AppNavigator = createAppContainer(StackNavigator);
export default {
  components: { Header }
}
</script>
