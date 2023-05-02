<template>
  <div class="contact-details">
    <h1 class="contact-heading">Contact:</h1>
    <p>Name: {{ name }}</p>
    <p>Website: {{ websiteAddress }}</p>
    <p>Address: {{ address }}</p>
  </div>
</template>

<script>
export default {
  props: ["name", "websiteAddress", "address"],
  data() {
    return {
      // name: "Pabel Mahbub",
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.contact-details {
  border: 1px solid red;
  margin: 11px 22px;
  padding: 22px;
}

.contact-heading {
  color: green;
}
</style>
