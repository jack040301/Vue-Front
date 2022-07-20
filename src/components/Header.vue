<script setup>
import imagePath from "@/assets/logo.png"



</script>
<template>
<div class="navbar bg-opacity-20 text-neutral-content">

   <div class="flex-1">
     <div class="w-25">
          <img :src="backimg" />
        </div>
  
   </div>
   
 


</div>


</template>



<script>


export default {
  components : {

  },
  data(){
   return {
      backimg : imagePath,
     
   }
  }
}
</script>