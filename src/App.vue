<template>
  <div id="app" class="container mt-5">
    <VeeValidationForm/>
  </div>
</template>

<script>
import VeeValidationForm from './components/VeeValidationForm'

export default {
  name: 'App',
  components: {
    VeeValidationForm
  }
}
</script>

<style>
@import url("https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css");
</style>
