<template>
  <div class="home">


    <Articles/>


  </div>
</template>


<script>
// @ is an alias to /src
import Articles from '@/components/Articles.vue'

export default {
  name: 'home',
  components: {
    Articles
  }
}
</script>


<style scoped>
  * {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
  }
</style>