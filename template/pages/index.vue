<template>
  <section class="container">
    <div>
      <logo/>
      <h1 class="title">
        {{msg}}
      </h1>
      <h2 class="subtitle">
        My  posh Nuxt.js project demo
      </h2>
      <nuxt-child />
    </div>
  </section>
</template>
<script>
  // import Logo from '~/components/Logo.vue'
  import Axios from 'axios'
  export default {
    layout: "main",

    components: {
      // Logo
    },
   async created(){
//     let {data}=await Axios.get('http://order.luckydd.cn/api/Commodity/classly')
    }
  }
</script>

<style lang="scss">
</style>
