<template>
  <div>
    <Head>
      <Title>Next Dojo | {{ product.title }}</Title>
      <Meta name="description" :content="product.description" />
    </Head>

    <ProductDetails :product="product" />
  </div>
</template>

<script setup>
const { id } = useRoute().params

const url = "https://fakestoreapi.com/products/" + id

const { data: product } = await useFetch(url, { key: id })

if (!product.value) {
  throw createError({ statusCode: 404, statusMessage: "Product not found" })
}

definePageMeta({
  layout: "products"
})
</script>

<style scoped></style>