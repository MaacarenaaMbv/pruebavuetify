<template>
    <h1>Login Form</h1>
    <v-sheet width="300" class="mx-auto">
    <v-form @submit.prevent>
      <v-text-field
        label="Email"
        prepend-inner-icon="mdi-email"
      ></v-text-field>
      <v-text-field
        label="Password"
        type="password"
        prepend-inner-icon="mdi-key"
      ></v-text-field>
      <v-btn type="submit" block class="mt-2">Submit</v-btn>
    </v-form>
  </v-sheet>
</template>

<script>
export default {
    name: "LoginComponent"
}
</script>

<style>

</style>