<script>
import NavbarComponent from "./components/NavbarComponent.vue";
import ProductsComponents from "./components/ProductsComponents.vue";
import CartComponent from "./components/CartComponent.vue";
export default {
  components: {
    NavbarComponent,
    ProductsComponents,
    CartComponent,
  },
};
</script>

<template>
  <div class="container">
    <NavbarComponent></NavbarComponent>
    <CartComponent></CartComponent>
    <ProductsComponents></ProductsComponents>
  </div>
</template>

<style lang="scss">
@import "./assets/all.scss";
.table-image {
  height: 100px;
  width: 100px;
  object-fit: cover;
}
.card-img-top {
  height: 200px;
  object-fit: cover;
}
</style>
