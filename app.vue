<template>
  <div class="d-flex align-center flex-column">
    <v-icon>mdi-home</v-icon>
    <v-card width="400">
      <v-card-title>This is a title</v-card-title>
      <v-card-subtitle>This is a subtitle</v-card-subtitle>
      <v-card-text> This is content </v-card-text>
    </v-card>
    <v-btn class="mt-10">Hello Sass Changes</v-btn>
    <v-radio-group>
      <v-radio label="Radio 1" value="1"></v-radio>
      <v-radio label="Radio 2" value="2"></v-radio>
      <v-radio label="Radio 3" value="3"></v-radio>
    </v-radio-group>
    <v-text-field
      label="Main input"
      hide-details="auto"
    ></v-text-field>
    <v-text-field label="Another input"></v-text-field>
  </div>
</template>

<script lang="ts">
export default defineComponent({
  setup(){
    console.log('hello')
  }
})
</script>
<style lang="scss">
@use './settings';
</style>
