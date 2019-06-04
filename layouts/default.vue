<template>
  <div>
    <appheader/>
    <nuxt />
    <appfooter/>
  </div>
</template>
<script>
import appheader from '../components/appheader';
import appfooter from '../components/appfooter';
export default {

  components:{

    appheader,
    appfooter
  }
  
}
</script>
