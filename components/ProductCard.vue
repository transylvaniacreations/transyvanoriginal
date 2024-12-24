<template>
  <div class="product-card">
    <img :src="product.image" :alt="product.name" />
    <h3>{{ product.name }}</h3>
    <p>{{ product.price }} RON</p>
    <button @click="addToCart">Add to Cart</button>
  </div>
</template>

<script>
export default {
  name: 'ProductCard',
  props: {
    product: Object,
  },
  methods: {
    addToCart() {
      // Implement add to cart functionality
    },
  },
};
</script>

<style scoped>
.product-card {
  border: 1px solid #ddd;
  padding: 1rem;
  text-align: center;
}
.product-card img {
  max-width: 100%;
  height: auto;
}
button {
  background-color: #333;
  color: #fff;
  border: none;
  padding: 0.5rem 1rem;
  cursor: pointer;
}
</style>
