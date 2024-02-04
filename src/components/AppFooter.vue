<!--SCRIPT-->
<script>
export default {
    data() {
        return {

        }
    }
}
</script>

<!--TEMPLATE-->
<template>
    <!--Footer-->
    <footer>
        <!--Contenitore del Footer-->
        <div id="footer-container" class="container">
            <!--Bottone del Footer-->
            <a href="#">SIGN-UP NOW!</a>
            <!--Follow Us-->
            <div id="follow-us">
                <h5>Follow Us</h5>
                <img src="../assets/img/footer-facebook.png" alt="fb">
                <img src="../assets/img/footer-twitter.png" alt="twitter">
                <img src="../assets/img/footer-youtube.png" alt="YT">
                <img src="../assets/img/footer-pinterest.png" alt="Pint">
                <img src="../assets/img/footer-periscope.png" alt="Periscope">
            </div>
        </div>
    </footer>
</template>

<!--STYLE-->
<style lang="scss" scoped>
/*Stile del footer*/
footer {
    height: 10vh;
    background-color: rgb(48, 48, 48);

    /*Stile del contenitore del footer*/
    #footer-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;

        /*Stile del bottone del footer*/
        a {
            text-decoration: none;
            color: white;
            border: 2px rgb(2, 130, 249) solid;
            padding: 10px;
            font-weight: bold;
        }

        a:hover {
            padding: 15px;
            background-color: rgb(2, 130, 249);
        }

        /*Stile del Follow Us*/
        #follow-us {
            display: flex;
            justify-content: center;
            align-items: center;

            /*Stile del titolo del Follow Us*/
            h5 {
                color: rgb(19, 83, 143);
                font-weight: bold;
                font-size: 30px;
                padding: 0 10px;
            }

            /*Stile delle immagini del Follow Us*/
            img {
                height: 40px;
                width: 50px;
                padding: 0 5px;
                cursor: pointer;
                filter: opacity(0.5);
            }

            img:hover {
                filter: opacity(1);
            }
        }



    }
}
</style>