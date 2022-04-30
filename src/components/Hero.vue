<template>
  <div class="container p-3">
      <div class="row">
          <div class="col-md-6">
               <carousel :items-to-show="1" transition="2000" autoplay="1" wrapAround="true"> 
                <slide v-for="slide in img_arr" :key="slide">
                    <img :src="slide.img" alt="">
                </slide>

               </carousel>
          </div>
          <div class="col-md-6">
              <h1 class="hero_heading">
                  <span class="text-primary">Book something awesome<span style="font-size:1rem;">&REG;</span></span>
                  <span>for your next event</span>
              </h1>
              <p class="info">
                  From birthday parties to weddings, we’ll help you book the best talent for any occasion.
              </p>
          </div>

          
      </div>

      <div class="row sBox_row" >
              <form action="#" class="nav_form">
                <div class="d-flex justify-content-between">
                    
                        <input type="search" name="" id="" class="sBox2" placeholder="What kind of talent or service can we help you find?">
                        <button class="btn btn-primary " style="padding-right: 2.5rem; padding-left: 2.5rem;">Search</button>
                        <!-- <img class="sBox_search_icon" src="https://cress.gigsalad.com/images/svg/standalone/navigation/search.svg" alt="">  -->
                </div>
            </form>
    </div>

        
  </div>

  
</template>

<script>
import 'vue3-carousel/dist/carousel.css';
import { Carousel, Slide, Pagination, Navigation } from 'vue3-carousel';
export default {
    components:{
    Carousel,
    Slide,
    Pagination,
    Navigation,
    },

    data(){
        return{
            img_arr:[
                {id:1,img:'https://cress.gigsalad.com/images/portraits/princess--421w.jpg'},
                {id:2,img:'https://cress.gigsalad.com/images/portraits/photographer--421w.jpg'},
                {id:3,img:'https://cress.gigsalad.com/images/portraits/violinist--421w.jpg'},
                {id:4,img:'https://cress.gigsalad.com/images/portraits/belly-dancer--421w.jpg'},
                {id:5,img:'https://cress.gigsalad.com/images/portraits/comedian--421w.jpg'},
                {id:6,img:'https://cress.gigsalad.com/images/portraits/rock-band--421w.jpg'},
                {id:7,img:'https://cress.gigsalad.com/images/portraits/caterer--421w.jpg'},
            ]
        }
    }
}
</script>

<style scoped>
.hero_heading{
    margin-bottom: 12px;
    line-height: 1.15em;
    font-weight: 700;
    font-size: 54px;
}

.info{
    font-weight: 400!important;
    font-size: 16px;
    line-height: 24px;
    margin-bottom: 12px;
}

.nav_form{
    flex-grow: 1;
    position: relative;
    margin-right: 36px;
    border-left: 1px solid #eff1f4;
    border-right: 1px solid #eff1f4;
}

.sBox_row{
    padding: 3rem;
    position: absolute;
    bottom: 1rem;
    width: 76%;
}

.sBox2{
    height: 90px;
    border: 0;
    padding-left: 64px;
    padding-right: 36px;
    font-size: 16px;
    margin-bottom: 0;
    position: relative;
    width: 100%;
    /* background: #EDF1F5!important; */
    background-color: rgba(244, 250, 255, 0.9);
    z-index: 999;
}

.sBox2:focus{
    outline: 1px solid #2690FF;
}

</style>