<template>

  <div>

    <p>{{message}}</p>


    <p>Image as an ASSET</p>
    <img src="~assets/test.jpg" />

    <q-space/>

    <p>Image as a STATIC</p>
    <img src="statics/test.jpg"/>


  </div>



</template>

<style>
</style>

<script lang="ts">
import Vue from 'vue'


export default Vue.extend({
  name: "PageIndex",


  data: function () {

    return {
      message: 'Vue is working'
    }
  }


}); //Vue.extend

</script>
