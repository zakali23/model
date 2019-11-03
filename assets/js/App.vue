<template>
<v-app>
    <v-alert
      v-model="alert"
      dismissible
      color="success"
      border="left"
      elevation="2"
      colored-border
      icon="mdi-check-all"
    >
     Votre Application à été bien <strong> installé</strong>.
    </v-alert>
</v-app>
</template>

<script>

export default {
  name: "App",
  data () {
      return {
        alert: true,
      }
    }
 
};
</script>

<style>
</style>