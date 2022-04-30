<template>
    <div class="container" >
        <div class="row justify-content-center p-3">
        <h4 class="my-4">
            <span>Whatever you’re planning,</span>
            <br>
            <span>make it extraordinary.</span>
        </h4>

    </div>
        <div class="row justify-content-center p-3">
            <h5 class="my-4">
                Musical Acts
            </h5>

        </div>

        <div class="row  my-4">
            
            <div class="col-md-3" style="width: 281px;">
                <router-link to="/pages/1">
                <div class="card1">
                    <div class="card_text">
                        <h4>Bands & Groups</h4>
                        <p>Blues Bands, Mariachis, Wedding Bands…</p>
                    </div>
                </div>
                </router-link>
            </div>
            
            <div class="col-md-3" style="width: 281px;">
                <router-link to="/pages/1">
                <div class="card1">
                    <div class="card_text">
                        <h4>Bands & Groups</h4>
                        <p>Blues Bands, Mariachis, Wedding Bands…</p>
                    </div>
                </div>
                </router-link>
            </div>
            
            <div class="col-md-3" style="width: 281px;">
                <router-link to="/pages/1">
                <div class="card1">
                    <div class="card_text">
                        <h4>Bands & Groups</h4>
                        <p>Blues Bands, Mariachis, Wedding Bands…</p>
                    </div>
                </div>
                </router-link>
            </div>
            
            <div class="col-md-3" style="width: 281px;">
                <router-link to="/pages/1">
                <div class="card1">
                    <div class="card_text">
                        <h4>Bands & Groups</h4>
                        <p>Blues Bands, Mariachis, Wedding Bands…</p>
                    </div>
                </div>
                </router-link>
            </div>
           
          
            
           
        </div>
    </div>
  
</template>

<script>
export default {
    

}
</script>

<style scoped>

a{
    text-decoration: none;
}

.card1{
    /* background: linear-gradient(to bottom, rgba(0,0,0,0.5), rgba(0,0,0,0.5) ), url('https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg'); */
    background: url(https://cress.gigsalad.com/images/home-slider-categories/BandsGroups.jpg);
    background-repeat: no-repeat;
    height: 40vh;
   
    background-position: center;
    background-size: contain;
    display: flex;
    flex-direction: column;
    justify-content: flex-end;
    
}

.card_text{
    background: linear-gradient(180deg,transparent,rgba(0,0,0,.75));
    border-radius: 4px;
    height: 50%;
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: flex-end;
    width: 100%;

}

.card_text h4{
    font-size: 18px;
    color: #fff;
}

.card_text p{
    font-size: 14px;
    color: #fff;
}

</style>