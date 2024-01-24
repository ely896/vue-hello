<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Wold',
      image: 'https://www.grazia.it/content/uploads/2023/04/GettyImages-fiori.jpg'
    }
  },

}



</script>

<template>
  <div>
    <h1>Hello {{ message }}</h1>
    <img :src="image" alt="">
  </div>
</template>

<style>

</style>
