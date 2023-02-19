<template>
    <header class="bg-transparent">
      <nav class="mx-auto max-w-7xl px-6 lg:px-8" aria-label="Top">
        <div class="flex w-full items-center justify-between border-b border-indigo-500 py-6 lg:border-none">
          <div class="flex items-center color-white">
            <h1>Propper.</h1>
            <!-- <div class="ml-10 hidden space-x-8 lg:block"> -->
<!--                  -->
            <!-- </div> -->
          </div>
          <div class="ml-10 space-x-4">
            <ul class="flex gap-4 color-white" >
    <li><NuxtLink to="/">Home</NuxtLink></li>
    <li><NuxtLink to="/about">About</NuxtLink></li>
    <li><NuxtLink to="/contact">Contact</NuxtLink></li>
    <li><NuxtLink to="/gallery">Gallery</NuxtLink></li>
    <li><NuxtLink to="/pricing">Pricing</NuxtLink></li>
</ul>
            <!-- <a v-for="link in navigation" :key="link.name" :href="link.href" class="text-base font-medium text-white hover:text-indigo-50">{{ link.name }}</a>  -->
            <!-- <a href="#" class="inline-block rounded-md border border-transparent bg-indigo-500 py-2 px-4 text-base font-medium text-white hover:bg-opacity-75">Sign in</a> -->
            <!-- <a href="#" class="inline-block rounded-md border border-transparent bg-white py-2 px-4 text-base font-medium text-indigo-600 hover:bg-indigo-50">Sign up</a> -->
          </div>
        </div>
        <!-- <div class="flex flex-wrap justify-center gap-x-6 py-4 lg:hidden"> -->
          <!-- <a v-for="link in navigation" :key="link.name" :href="link.href" class="text-base font-medium text-white hover:text-indigo-50">{{ link.name }}</a> -->
        <!-- </div> -->
      </nav>
    </header>
    <div>
        <slot/>
    </div>
  </template>

<style scoped>
.router-link-exact-active{
    text-decoration: underline;
}

header {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  /* padding: 20px; */
  color: white;
  text-shadow: 1px 1px 1px black;
}



</style>
  
  <!-- <script setup> -->
<!-- //   const navigation = [ -->
    <!-- // { name: 'Home', href: '/' }, -->
    <!-- // { name: 'About', href: '/about' }, -->
    <!-- // { name: 'Pricing', href: '/pricing' }, -->
    <!-- // { name: 'Gallery', href: '/gallery' }, -->
    <!-- // {name: 'Pricing', href: '/pricing'} -->
<!-- //   ] -->
<!-- //   </script> -->


<!-- <template>
    <div>
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-betwwen">
            <h3>Propper</h3>
            <ul class="flex gap-4">
                <li><NuxtLink to="/">Home</NuxtLink></li>
                <li><NuxtLink to="/about">About</NuxtLink></li>
                <li><NuxtLink to="/contact">Contact</NuxtLink></li>
                <li><NuxtLink to="/gallery">Gallery</NuxtLink></li>
                <li><NuxtLink to="/pricing">Pricing</NuxtLink></li>
            </ul>
        </nav>
    </header>
   <div class="container mx-auto p-4 ">
      <slot />
   </div>
    </div>
</template>

<style scoped>
.router-link-exact-active{
    color:#12b488
}
</style>







 -->
