<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Monster</span>
        <span class="font-weight-light">PROJECT</span>
      </v-toolbar-title>
    </v-app-bar>
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import { VApp, VAppBar, VToolbarTitle, VContent } from 'vuetify/lib'


export default {
  name: 'App',
  components: {
    HelloWorld,
    VApp,
    VAppBar,
    VToolbarTitle,
    VContent,
  },
  data: () => ({
    //
  }),
};
</script>
