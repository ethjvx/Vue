<template>
  <div>
      xxx
      {{ msg }}
      <p>llal</p>
      <base-son />
  </div>
  
</template>

<script>
import baseSon from './Son';
export default {
    components: {
        baseSon
    },
    data(){
        return {
            msg:"hello word"
        }
    }
}
</script>

<style>
    div {
        background-color: red;
    }
</style>