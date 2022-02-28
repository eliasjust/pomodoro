<!-- Please remove this file from your project -->
<template>
<div class="h-screen w-screen flex place-items-center justify-center">

  <div class="text-9xl">
    {{new Date(timeleft)}}
  </div>

</div>
</template>

<script>

export default {
  name: 'NuxtTutorial',

  methods:{
    countTime(){
      let time=timeleft.sprit(',')
      time[1]++;

    }



  },
  data(){
    return {
      timeleft:'03:40',
      time:3
    }
  },
  mounted() {
  //  countTime();
  },


}


</script>

<style>


</style>
