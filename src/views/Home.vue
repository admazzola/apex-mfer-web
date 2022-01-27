<template>

<div>

    

   <div class="section bg-primary border-b-4 border-black px-0 lg:px-1">
 
     <div class=" ">
        <Navbar         
       />
     </div>

 



     <div class="container margin-center bg-gray-100" style="">
       <div class="hero-text w-row relative" style="min-height:300px;" >

         
          <img src="@/assets/images/blob1.png" class="absolute" style="top:-36px;left:-8px;z-index:0"></img>
           <img src="@/assets/images/blob2.png" class="absolute" style="top:-36px;right:-20px;z-index:0"></img>

             <img src="@/assets/images/prettybad_wen.gif" class="absolute" style="width:140px;top:-26px;right:70px;z-index:1"></img>

           <img src="@/assets/images/gm_mfers2.gif" class="absolute" style="width:140px;top:86px;right:20px;z-index:0"></img>
         
       </div>
       <div class="div-block">
        coming soon ...
       </div>
     </div>
   </div>

   <div class="section autospacing">
     <div class="container margin-center ">
       <div class="w-row">
         <div class="w-col w-col-6 mt-4">
           <div class="intro-list">
            ... 
           </div>
         </div>
         <div class="w-col w-col-6">
          ...
         </div>
       </div>
     </div>
   </div>


    <div class="section bg-gray-700">


     <div class="container margin-center">
       <div class="w-row py-8">
          <div class="w-col w-col-4">
             
         </div>
         <div class="w-col w-col-4">
           <a href="https://discord.0xbtc.io" target="_blank">
            <div class="bg-purple-600 hover:bg-purple-700 text-white p-4 rounded"> <img src="@/assets/images/discord-icon.svg" width="40" height="40" alt=""> <div class="text-md text-white inline pl-8">Join us in Discord</div></div>
          </a>
          </div>
         <div class="w-col w-col-4">
            
         </div>
       </div>
     </div>



   </div>


   <div class="section">
       <div class="container margin-center">
 section

      </div>
   </div>



   

  <Footer/>

</div>
</template>


<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'Home',
  props: [],
  components: {Navbar,Footer},
  data() {
    return {

    }
  },
  methods: {

  }
}
</script>
