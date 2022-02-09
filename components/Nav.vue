<template>
  <nav>
    <NuxtLink to="/">HOME</NuxtLink>

    <NuxtLink to="/about">ABOUT</NuxtLink>

    <NuxtLink to="/contact">CONTACT</NuxtLink>
  </nav>
</template>

<script>
export default{
  setup(){
    myObject:{
      link:""
    }
  }
}
</script>