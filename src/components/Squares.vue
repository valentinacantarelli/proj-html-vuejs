<template>
  <div class="square">
    <img src="../assets/img/h-2-port-img-1.jpg" alt="">
    <img src="../assets/img/h-2-port-img-2.jpg" alt="">
    <img src="../assets/img/h-2-port-img-3.jpg" alt="">
    <img src="../assets/img/h-2-port-img-4.jpg" alt="">
    <img src="../assets/img/h-2-port-img-5.jpg" alt="">
    <img src="../assets/img/h-2-port-img-6.jpg" alt="">
    <!-- <ul>
      <li v-for="(img,index) in pictures" :key="index">
        <img :src="('../assets/img/'+ img.numbers )" alt="">
      </li>
    </ul> -->
  </div>
</template>

<script>
export default {
    name:"Squares",
    data(){
      return{
        pictures:[
          {
            numbers:"h-2-port-img-1.jpg",
          },
          {
            numbers:"h-2-port-img-2.jpg",
          },
          {
            numbers:"h-2-port-img-3.jpg",
          },
          {
            numbers:"h-2-port-img-4.jpg",
          },
          {
            numbers:"h-2-port-img-5.jpg",
          },
          {
            numbers:"h-2-port-img-6.jpg",
          },
        ]
      }
    }
}
</script>

<style  lang="scss" scope>
.square{
  margin-top: 180px;
  display: flex;
  flex-wrap: wrap;
  img{
    width: calc(100% / 3);
  }
}
</style>