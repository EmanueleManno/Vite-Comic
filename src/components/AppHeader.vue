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
    <!--Header-->
    <header>
        <!--Contenitore dell'Header-->
        <div class="container" id="header-content">
            <!--Logo dell'Header-->
            <img src="../assets/img/dc-logo.png" alt="Logo">
            <!--Menù Navbar-->
            <nav>
                <a href="#">Characters</a>
                <a href="#">Comics</a>
                <a href="#">Movies</a>
                <a href="#">TV</a>
                <a href="#">Games</a>
                <a href="#">Collectibles</a>
                <a href="#">Videos</a>
                <a href="#">Fans</a>
                <a href="#">News</a>
                <a href="#">Shop</a>
            </nav>
        </div>
    </header>
</template>

<!--STYLE-->
<style lang="scss" scoped>
/*Stile Header*/
header {
    height: 10vh;
    background-color: white;
    border: 2px solid black;

    /*Stile Header Content*/
    #header-content {
        display: flex;
        align-items: center;
        justify-content: space-between;
        height: 100%;

        /*Stile delle a*/
        a {
            text-decoration: none;
            padding: 0 10px;
            color: rgb(154, 174, 193);
            font-weight: bold;
            font-size: 20px;
        }

        a:hover {
            color: black;
            font-size: 25px;
        }
    }
}

/*Stile Immagine Header*/
img {
    height: 75px;
    width: 75px;
}
</style>