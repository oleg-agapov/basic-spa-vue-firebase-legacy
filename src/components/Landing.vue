<template>
  <v-layout column>
    <v-flex xs12 class="text-xs-center" mt-5>
      <h3>Welcome to Awesome App</h3>
    </v-flex>
    <v-flex xs12 sm6 offset-sm3 mt-3>
      <blockquote>
        It's a basics application with authentication, real-time database and hosted on Google Firebase hosting
      </blockquote>
    </v-flex>
    <v-flex class="text-xs-center" mt-5>
      <v-btn primary to="/signup">Sign Up</v-btn>
      <v-btn to="/signin">Sign In</v-btn>
    </v-flex>
  </v-layout>
</template>

<script>
export default {}
</script>
