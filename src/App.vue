<template>
  <MyBtn>Banana</MyBtn>
  <MyBtn 
      :color=color
       ><span style="color: red;">banana</span>
      </MyBtn>
  <MyBtn large
      color ="royalblue"
      >apple</MyBtn>
  <MyBtn>cherry</MyBtn>
  <button>Banana</button>
</template>

<script>
import MyBtn from '~/components/MyBtn'

export default {
    components: {
      MyBtn
    },
    data(){
      return{
        color : "#000"
      }
    }
}
</script>

<style>
  

</style>