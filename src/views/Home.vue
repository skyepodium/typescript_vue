<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <message />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import message from '@/components/message.vue' //@를 붙여주면 src로 인식된다. 
@Component({
  components: {
    message
  },
})
export default class Home extends Vue {}
</script>
