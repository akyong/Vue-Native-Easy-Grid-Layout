<template>
    <root>
        <AppNavigation />
    </root>
</template>

<script>
import * as React from 'react'
import {
  createAppContainer,
  createStackNavigator,
} from "vue-native-router";
import { Root } from "native-base"
// const HomeStack = createStackNavigator(
//   {
//     Master : MenuMaster,
//     Login : Login,
//     Register : Register,
//     MenuRegister : MenuRegister,
//     Otp : Otp,
//     MenuLogin : MenuLogin
//   },
//   {
//     initialRouteName : 'Master',
//     headerMode : 'none'
//   }
// )
// const AppNavigation = createAppContainer(HomeStack)
// export default {
//     components: {
//         AppNavigation, Root
//     },
//     data () {
//         return{
//         }
//     }
// }
</script>