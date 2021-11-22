<template>
<div>
  <figure>
    <nuxt-img :src="info.image" sizes="sm:100vw md:50vw lg:250px"/>
    </figure>
</div>
</template>
<script>
export default {
  props:["pageInfo"]
    
  }
</script>