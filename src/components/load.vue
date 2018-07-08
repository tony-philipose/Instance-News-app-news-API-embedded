<template>
  <p v-if="itemsInStock > 10"> in stock.</p>
  <h1>ss</h1>
</template>

<script >
export default {
  name: 'load',
  data () {
    return {
     itemsInStock: 70
    }
  },
  
}
</script>
  
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped >

</style>
