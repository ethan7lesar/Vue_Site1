<template>
  <div class="home">
    
    <HomeComp msg="Welcome to Your Vue.js App"/>

  </div>
</template>

<script>
// @ is an alias to /src
import HomeComp from '@/components/HomeComp.vue';

export default {
  name: 'HomeView',
  components: {
   
    HomeComp
}
}
</script>
