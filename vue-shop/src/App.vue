<template>
  <div id="app">
    <b-container>
      <product-list></product-list>
    </b-container>
    
  </div>
</template>

<script>
import ProductList from './components/ProductList'
export default {
  name: 'app',
  components: {
    ProductList
  }
}
</script>