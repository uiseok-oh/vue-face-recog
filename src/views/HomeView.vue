<template>
  <div class="home">
    <FaceRecognition></FaceRecognition>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import FaceRecognition from '@/views/FaceRecognition.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld,
    FaceRecognition
  }
}
</script>
