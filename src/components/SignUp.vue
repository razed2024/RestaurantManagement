<script>
export default {
    name :'SignUp',
   
}


</script>

<template>
  <div class=" w-full flex flex-col items-center justify-between text-center mt-8 ">
    <div class=" w-full flex flex-col items-center">
      <img class="text" src="../assets/restaurant.png" alt="">
     <h1 class="text-blue-700 text-xl font-bold text-[20px]"> Sign Up</h1>
    </div>
    
    <div class="register w-full m-5 flex flex-col items-center">
      <input type="text" placeholder="Enter Name" class="m-3 border border- border-green-300 hover:border-red-400 rounded-xl p-4 w-[350px]">
      <input type="email" placeholder="Enter Email" class="m-3 border border- border-green-300 hover:border-red-400 rounded-xl p-4 w-[350px]">
      <input type="password" placeholder="Enter Password" class="m-3 border border- border-green-300 hover:border-red-400 rounded-xl p-4 w-[350px]">
      <button class=" bg-teal-500 p-3 text-lg text-slate-200 rounded-full mt-2 py-3 px-10 hover:bg-red-400 cursor-pointer"> Sign Up</button>


    </div>



  </div>
</template>

<style>

</style>
