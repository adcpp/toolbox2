<template>
  <app-quote>
      <h2>{{produto}}</h2>
      <p>{{valor}}€</p>
  </app-quote>
</template>
<script>
import appQuote from '@/components/app-quote';
export default {
    compomemts:{
        appQuote
    },
    props:{
        produto:{
            tipe: String,
            required: true
        },
        valor:{
            type: Number,
            required: true
        }
    }
  
}
</script>

