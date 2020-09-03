<template>
    <div class="">
      <img :src="image">
    </div>
</template>


<script>
  import image from "../assets/back.jpg"

  export default {
    data: function () {
      return {
        image: image
      }
    }
  }
</script>
