<template>
  <v-app>
    <header-component />
    <nuxt />
    <footer-component />
  </v-app>
</template>

<script>
//@ 나 ~ 표시는 최상위 폴더
import HeaderComponent from "@/components/HeaderComponent";
import FooterComponent from "@/components/FooterComponent";
export default {
  components: {
    HeaderComponent,
    FooterComponent
  }
};
</script>
