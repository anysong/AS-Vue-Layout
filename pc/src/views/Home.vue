<template>
  <div class="home">
    <div>2222</div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  created(){
    console.log('env', process)
    console.log('env1', process.env)
  }
}
</script>
