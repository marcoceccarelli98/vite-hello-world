<script>
export default {
  name: "AppHero",
  data() {
    return {

      imageName:"jumbo.png",
    };
  },

  methods:{
    getImagePath: function(img){
      return new URL(`../assets/${img}`,import.meta.url).href;
    }
  }
};
</script>

<template>
  <img :src="getImagePath(imageName)"></img>
</template>

<style>
img{
  width: 100%;
}
</style>