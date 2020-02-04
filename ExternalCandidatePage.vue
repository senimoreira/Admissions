<template>
  <div class="external-candidate">
    <div class="centered">
      <h1> External Candidate </h1>
      <p> What is your email? </p>
      <input
        v-model="email">
      <p>Email inserted is: {{ email }}</p>
    </div>
  </div>
</template>

<script src="https://www.google.com/recaptcha/api.js" async defer></script>

<script>
export default {
  data () {
    return {
      email: ''
    }
  }
}
</script>

<style >
.external-candidate {
  text-align: center;
}
.centered {
  margin-top: 15%;
}
</style>
