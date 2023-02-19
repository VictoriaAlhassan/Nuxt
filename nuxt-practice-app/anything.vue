<template>
 <HomeWelcome/>
 <!-- <counter/> -->
<component :is="counter"/>

<NuxtPage/>
</template>

<script setup>
 const counter = resolveComponent('counter')

</script>










