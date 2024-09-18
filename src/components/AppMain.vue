<script>


</script>


<template>
<div>
    <div class="content">
         <-- Content goes here -->
    </div>
    <div class="links">

        <!-- Link principali con sfondo blu -->
        <ul>
            <li>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#"> DIGITAL COMICS </a>  
            </li>
            <li>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <a href="#"> MERCHANDISE </a>
            </li>
            <li>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <a href="#"> SUBSCRIPTION </a>
            </li>
            <li>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="" class="shop-locator">
                <a href="#"> COMICS SHOP LOCATOR </a>
            </li>
            <li>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <a href="#"> DC POWER VISA </a>
            </li>
        </ul>
    </div>
   
</div>


</template>

<style lang="scss" scoped>

@use '../assets/scss/partials/variables' as *;

div {
    background-color: black;
    height: 300px;

}

.content {
    color: white;
    padding: 30px;
    text-align: left;
}

.links {
    background-color: $mainColor;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;

}


ul {
    list-style: none;
    display: flex;
    justify-content: center;


    li {
      text-transform: uppercase;
      padding: 20px;
      display: flex;
      align-items: center;


      img {
        width: 45px;
      }
    }

    a {
        color: white;
        text-decoration: none;
        padding-left: 10px;
    }
}

.shop-locator {
    width: 40px;
}
</style>