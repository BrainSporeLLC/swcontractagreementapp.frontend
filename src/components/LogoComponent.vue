<template>
    <span>
        {{ logo }}
    </span>
</template>
<script>
 import logo from "../../public/meta-ajax-02.png";

 export default {
  data(){
    return {
      logo: logo
    }
  }
 }
</script>