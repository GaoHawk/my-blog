<template lang="html">
  <div class="foot">
    <div class="container">
      <!-- <run-time></run-time> -->
      <p>Made
        <i class="fa fa-heart"></i> By Gaohawk.
      </p>
    </div>
  </div>
</template>

<script>
  import runTime from '@/components/runTime.vue'
  export default {
    components: {
      runTime
    }
  }
</script>

<style lang="css" scoped>
    .foot {
      color: #888;
      font-size: 12px;
      visibility:hidden;
      position: relative;
      margin-top: 40px;
      padding: 15px 0 10px;
      background-color: rgb(46, 47, 47);
      text-align: center;
      width: 100%;
      /* position: fixed; */
      /* bottom: 0; */
    }
   @media only screen and  (max-device-width:960px) {
    .foot {
      visibility:visible;
      position: relative;
      margin-top: 40px;
    }
  }


</style>
