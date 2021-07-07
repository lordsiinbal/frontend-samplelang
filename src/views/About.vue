<template>
  <div class=" relative flex-col text-center h-screen space-y-4 p-4 border-blue-500 border-2">
    <div class="about bg-red-300 font-bold border-2 border-red-500 text-center">
    <h1 class="text-3xl">Bicol University</h1>
  </div>
  <nav class="border-2 border-red-500 py-2 flex justify-evenly">
    <a class="px-4 border-2 border-red-500">Home</a>
    <a class="px-4 border-2 border-red-500">About</a>
    <a class="px-4 border-2 border-red-500">Contact</a>
  </nav>
  <div class="border-2 h-auto
   border-red-500 p-2 gap-4 grid    grid-cols-2">
    <div class="border-2 border-red-500 text-justify ">Lorem ipsum dolor sit amet, consectetur
       adipisicing elit. Odio saepe 
       quo tenetur quos
        totam et similique
         quam sapiente dolorem? 
         At dolores reiciendis 
         eveniet ipsa quod architecto 
         aspernatur, cum sed temporibus?</div>
    <div class="border-2 border-red-500 row-span-2">2</div>
    <div class="border-2 border-red-500  ">3</div>
  </div>
  <div class="absolute  w-full  left-0 bottom-0 border-2 border-red-500">
    <Footer/>
  </div>
  
  </div>
</template>
<script>
import Footer from '../views/footer.vue'
export default {

components:{
  Footer
}
}
</script>
<style scoped>

</style>