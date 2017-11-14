<template>
    <div style="font-size:1.2rem">
      <headers></headers>
    </div>

    
</template>


<script>

import headers from './components/headers.vue'
    export default{

        data(){
            return{
                title: "first vue file"
            }
        },
        components:{
          "headers": headers
        },
        methods:{
          greeting: function(){
            return "hello jesse"
          }
        }
    }
</script>