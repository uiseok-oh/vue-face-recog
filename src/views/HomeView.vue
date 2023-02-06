<template>
  <div class="home">
    <FaceRecognition ></FaceRecognition>
    <HelloWorld msg="10분마다 기록됩니다."/>
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
