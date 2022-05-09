<template>
 
    <section>
      <div class="container">
        <div class="row">
          <div class="col-6 col-md-4 col-lg-3 mb-3">

          </div>

        </div>
        <p>prova</p>
      </div>
        
    </section>
  
</template>

<script>
export default {
  name: 'AppGrid',
  components:{
    
  },
  data(){
    return {
     apiPath: 'https://flynn.boolean.careers/exercises/api/array/music',
    }
  }

 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
section{
  background-color: #1E2D3B;
  height:calc(100vh - 60px);
}
</style>
