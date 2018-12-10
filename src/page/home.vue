<template>
  <div class="home_container">
      <itemcontainer father-component="home"></itemcontainer>
  </div>
  
</template>
<script>
import itemcontainer from '../components/itemcontainer.vue'
export default {
  name: 'home',
  components: {
      itemcontainer
  },
    data () {
      return {
        
      }
    }
}
</script>
<style scoped>

</style>

