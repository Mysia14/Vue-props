<template>
  <header>
    <h1>{{pageInfo.pageName}}</h1>
    <nuxt-img :src="siteInfo.image"></nuxt-img>
    </header>
</template>
<script>
export default {
  props: ["siteInfo"]
    
  }
</script>