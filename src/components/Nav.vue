<template>
    <nav class="nm p-2">
        <div class="nm_sec">
            <router-link to="/">
            <img src="https://cress.gigsalad.com/images/logo.svg" style="width: 60px; height: 60px;" alt="">
            </router-link>

            <a class="menu ml-3" href="#">Menu</a>
        </div>

        <form action="#" class="nav_form">
            <div class="nm_sec">
                <input type="search" name="" id="" class="sBox" placeholder="What kind of talent or service can we help you find?">
                <img class="sBox_search_icon" src="https://cress.gigsalad.com/images/svg/standalone/navigation/search.svg" alt="">
            </div>
        </form>

        <div class="nm_sec">
            <a href="#" class="heart_icon" >
                <img class="" src="https://cress.gigsalad.com/images/svg/standalone/navigation/heart.svg" alt="">
            </a>
            <a href="#" class="menu">Login</a>
            <a href="#" class="mr-2 btn btn-primary" >List your services</a>
        </div>

        
    </nav>
</template>

<script>
export default {

}
</script>

<style >

.nm
 {
    display: flex;
    justify-content: space-between;
    padding: 0 36px;
    background-color: #fff;
    border-bottom: 1px solid #eff1f4;
}

.nm_sec{
    display: flex;
    align-items: center;
}

.menu{
    font-size: 15px;
    font-weight: 400;
    color: #3d464d;
    padding: 8px 0;
    margin-right: 36px;
}

.menu:focus, .menu:hover {
    text-decoration: none;
    opacity: .75;
}

.nav_form{
    flex-grow: 1;
    position: relative;
    margin-right: 36px;
    border-left: 1px solid #eff1f4;
    border-right: 1px solid #eff1f4;
}

.sBox{
    height: 90px;
    border: 0;
    padding-left: 64px;
    padding-right: 36px;
    font-size: 16px;
    margin-bottom: 0;
    position: relative;
    width: 100%;
}
.sBox:focus{
    outline: none !important;
}

.sBox_search_icon {
    position: absolute;
    left: 36px;
    top: 50%;
    transform: translateY(-50%);
    height: 18px;
    width: 18px;
    pointer-events: none;
    filter: invert(26%) sepia(6%) saturate(1203%) hue-rotate(164deg) brightness(90%) contrast(88%) opacity(19%);
}

.heart_icon {
    font-size: 15px;
    font-weight: 400;
    color: #3d464d;
    padding: 8px 0;
    margin-right: 36px;
}

</style>