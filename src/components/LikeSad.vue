<script setup >
import { ref } from "vue";
const like = ref(50);
const sed = ref(100);

function  likeClick() {
  like.value +=50;
}
function sadClick(){
  sed.value -=500;
}

</script>

<template>
 <div>
   <button @click="likeClick()">ปุ่ม Like</button>
   {{ like }}
   <button @click="sedClick()">ปุ่ม Sad</button> {{ sad }}
   </div>
</template>

<style scoped></style>