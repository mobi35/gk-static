<template>


<div class=" h-screen">

<div class="flex justify-center  flex-wrap  mt-20">

  <div  class="image max-h-40 mx-10"><div class="mt-10"></div>
  <img class="  h-600" src="~/assets/products/p3.jpg"/>
  </div>

  <div class="description mx-10 justify-start">
    <div class="mt-10"></div>
      <h1 class=" font-sans tracking-widest text-4xl">WALK BY FAITH SOCKS</h1>

    <p class="font-serif text-2xl underline">500.00 PHP</p>

   <div class="mt-10"></div>

    <label>Size</label>
<v-select  :options="[{label: 'Small', code: 'ca'},{label:'Medium',code:'med'},{label:'Large',code:'large'}]"></v-select>
 <div class="mt-2"></div>
<label>Quantity</label>
<input value="1" class="block border border-gray-400 outline-none p-2  h-8 rounded-md " type="number" />
   <div class="mt-10"></div>
   <div class="mt-10"></div>

 <button class=" tracking-wider  h-16 border border-black w-full transition ease-out  duration-300 hover:bg-black hover:text-white hover:border-white "> ADD TO CART </button>
 <div class="mt-6"></div>
 <div class=" max-w-lg ">
   Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic
 </div>
  </div>


</div>

</div>
</template>

<script>
export default {

}
</script>

<style>

</style>
