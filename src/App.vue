<template>
  <AppNavbar />
  <AppHeader />
  <AppTable />
</template>

<script>
import AppNavbar from "./components/AppNavbar.vue";
import AppHeader from "./components/AppHeader.vue";
import AppTable from "./components/AppTable.vue";

export default {
  name: "App",
  components: {
    AppNavbar,
    AppHeader,
    AppTable,
  },
};
</script>

<style>
#app {
  font-family: Montserrat, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
}
body {
  margin: 0px;
}
</style>
