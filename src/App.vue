<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <ContactDetails
    name="Mxcç-Rahman Pabel"
    websiteAddress="www.2go.com"
    address="Noakhali"
  />
  <ContactDetails
    name="Pabel"
    websiteAddress="www.3go.com"
    address="Chittagong"
  />
  <ContactDetails name="Mahbub" websiteAddress="www.go.com" address="Dhaka" />
</template>

<script>
import ContactDetails from "./components/ContactDetails.vue";

export default {
  name: "App",
  components: {
    ContactDetails,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
