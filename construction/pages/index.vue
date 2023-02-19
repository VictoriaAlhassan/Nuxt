<template>
    <div class="homepage">
        <div class="overlay"></div>
      <div class="homepage-content">
        <h1>Get Ready.</h1>
        <p>We're finishing!</p>
      </div>
    </div>
    <div class=" services flex justify-center items-center h/2-screen">
        <h1>Our Services</h1>
    </div>
     <p class="paragraph">fxbgjjjjllkmmb vxewdcgvhnhjjgvfcdxwfhgvdggjhkhvcdsgv
                              cgvmjnkjnkkdffghjjnkjgfgjkjnvgfdshjhjvgfcgft</p>

               <div class=" grid grid-cols-4 gap-4">
                <div >
                   <img src='/excavator.jpg' alt="Fast Service" class="colorize" />


                   <div class=" justify-center items-center"><h2>Fast Services</h2></div>
                      <div><p>vbvhbjjhgcuabnxkjxnkbczvhgvhzjhhBGvcjcjhcbgcvhbjdhcnz<br>
                   sbkjnvkdjvkdjhvkdmkzjvbdjxhvbdjvhbjdxhbvjxhbvjhvbjdhbvzj
                          </p>
                </div>

                <div>
                    <img src="/construction.png" alt="rennovation"/>
                </div>
                </div>
                
                
                
                
               </div>   
  </template>
  

<script setup>

</script>

<style scoped>



.homepage {
  background-image: url('/static/building.jpg');
  background-size: cover;
  background-position: center;
  height: 100vh;
  display: flex;
  align-items: center;
  /* position:relative */
}
img{
    filter:saturate(100%) hue-rotate(500deg);
    width:37px;
    height:37px;
    /* margin-left: 50px; */
}
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(1.5, 1.5, 1.5, 1.5); /* adjust the alpha value to control the darkness */
  z-index: -1;
}

.homepage-content {
  margin-left: 50px; 
  color: white;
  text-shadow: 1px 1px 1px black;
  font-size: 80px;
  font-style: bold;
}
.services h1{
    font-size: 25px;
}
.paragraph{
 display: flex;
 justify-content: center; 
 align-items: center;  
}
 
</style>