<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burguer:</h1>
    <BurguerForm />
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import BurguerForm from '../components/BurguerForm.vue'
// @ is an alias to /src

export default {
  name : 'HomeView',
  components: {
    Banner,
    BurguerForm
  }
}
</script>
