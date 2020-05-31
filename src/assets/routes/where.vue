<template>
  <div class="where">
    <div class="flex mt-24">
      <div class="object-contain pr-5">
        <b-carousel
          class="w-100"
          id="carousel-fade"
          fade
        >
          <b-carousel-slide
            img-src="https://www.revolvermag.com/sites/default/files/styles/banner/public/media/images/article/swanscatherine-ceresole.jpg"
          ></b-carousel-slide>
        </b-carousel>
        <div>
          <h3 class="mt-5 font-bold">Bar Celona</h3>
          <p>C/ d'en Pepí 64 - 08004<br>
          Barcelona</p>
        </div>  
      </div>
      <div class="break"></div>
      <div class="w-full overflow-auto">    
        <div class="grid">
          <div class="item-1 m-5">
            <h2>AND</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/w5ZkzUGKQzo" />
          </div>
          <div class="item-1 m-5">
            <h2>HERE</h2>
          </div>       
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/edyKvdCqodQ" />
          </div>  
          <div class="item-1 m-5">
            <h2>WE HAVE</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/MaCQAxkLcYk" />
          </div>
          <div class="item-1 m-5">
            <h2>A SELECTION</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/Qr_yDyhv0kc" />
          </div>
          <div class="item-1 m-5">
            <h2>OF</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/GC3uv_aYDPI" />
          </div>
          <div class="item-1 m-5">
            <h2>MUSIC</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/ikCCQFKvYcc" />
          </div>
          <div class="item-1 m-5">
            <h2> & </h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/6qDq9eGUmMI" />
          </div>
          <div class="item-1 m-5">
            <h2>VIDEOS</h2>
          </div>
          <div class="item">
            <LazyYoutubeVideo src="https://www.youtube.com/embed/n8_ryhF690M" />
          </div>
          
        </div>
      </div>
    </div>
  </div>       
</template>

<script>
import LazyYoutubeVideo from "vue-lazy-youtube-video";
import VLazyImage from "v-lazy-image";

export default {
  name: "where",
  components: {
    LazyYoutubeVideo,
    VLazyImage,
  }
};
</script>
