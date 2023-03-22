<script>
export default {
    data(){
        return {
            img: "src/assets/konomorglda.png",
        }
    }
}
</script>

<template>
    <div class="img">
       <img :src="img" alt=""> 
    </div>
  
</template>

<style scoped>
    .img {
        height: 500px;
        max-width: 1000px;
        margin: 0 auto;
    }
    img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
</style>
