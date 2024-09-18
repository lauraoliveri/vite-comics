<script>
import AppMain from './AppMain.vue'
export default {
  data() {
    return { 
     
    }
  }
}

</script>

<template>
    <footer>
        <div class="footer-top">
             <!-- Footer top -->
            <div>
                <h3>DC Comics</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
            </div>
            <div>
                <h3>DC</h3>
                <ul>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Ad Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
            </div>
            <div>
                <h3>Sites</h3>
                <ul>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">Mad Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
        </div>

        <div class="footer-bottom">
            <!-- Footer bottom -->
            <div class="sign-up">
                <button>SIGN-UP NOW!</button>
            </div>

            <div class="social-icons">
                <!-- Socials -->
                 <span class="follow">
                    FOLLOW US!
                 </span>
                <img src="../assets/img/footer-facebook.png" alt="Facebook">
                <img src="../assets/img/footer-twitter.png" alt="Twitter">
                <img src="../assets/img/footer-youtube.png" alt="YouTube">
                <img src="../assets/img/footer-pinterest.png" alt="Pinterest">
                <img src="../assets/img/footer-periscope.png" alt="Maps">
            </div>
        </div>
            
    </footer>


</template>


<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.footer-top {
    margin-top: 150px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    height: 400px;


    ul {
        text-align: left;
    }
    a {
        color: white;
        opacity: 0.5;
    }

    h3 {
        color: white;
    }
}

.footer-bottom {
    display: flex;
    justify-content: space-between;
    padding: 30px;
    background-color: $mainGrey;

    
    .social-icons {
    text-align: center;
    margin-top: 20px;
    }

    .social-icons img {
    width: 30px;
    margin: 0 10px;
    }

    .sign-up {
    text-align: center;

        button {
        background-color: $mainGrey;
        color: white;
        border: 3px solid $mainColor;
        padding: 15px 30px;
        font-size: 16px;
        cursor: pointer;
        }
    }

    .follow {
        color: $mainColor;
        font-size: larger;
        font-weight: bold;
        padding: 5px;
    }

}
</style>
