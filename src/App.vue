<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue" ;
import FooterComp from "./components/template/FooterComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
  <FooterComp />
</template>

<style>
@import '@/assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

a {
 color: inherit;
 text-decoration: none;
}
header {
  height: 15%;
  background-color: rgb(59, 59, 127);
  color: white;
  font-size: 1.3rem;
  padding-left: 2%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

header span {
  padding: 0 20px;
}

main {
  height: 70%;
}
</style>
