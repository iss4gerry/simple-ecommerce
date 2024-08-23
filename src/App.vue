<template>
  <div id="app" class="container mt-5">
    <h1>Mayu Shop</h1>
    <p class="animate__animated animate__fadeInRight">
      Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolorem impedit voluptates, ex culpa, mollitia laudantium et dignissimos ut eos recusandae excepturi beatae consectetur voluptatibus. Et odit dolorem necessitatibus doloribus nulla?
    </p>
    <font-awesome-icon icon="shopping-cart"></font-awesome-icon>
    <price :value="4.23"></price>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import Price from './components/Price.vue'

export default {
  name: 'App',
  components: {
    FontAwesomeIcon,
    Price
  }
}
</script>

