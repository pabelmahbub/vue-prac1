<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <ContactDetails
    v-for="contact in contacts"
    :key="contact.name"
    :name="contact.name"
    :address="contact.address"
    :website="contact.website"
  ></ContactDetails>
</template>

<script>
import ContactDetails from "./components/ContactDetails.vue";

export default {
  name: "App",
  components: {
    ContactDetails,
  },
  data() {
    return {
      contacts: [
        { name: "Mahbub", website: "www.profile.com", address: "Dhaka" },
        { name: "Pabel", website: "www.ghghgh.com", address: "Tokyo" },
        { name: "Rahman", website: "www.pabelmahbub.com", address: "Noakhali" },
      ],
    };
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
