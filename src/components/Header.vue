<template>
    <div class="ps-header-bg">
        <div>
            <a href="http://puneetsoni.com">
                <img class="ps-header-logo" src="../assets/icons/ps-logo-02.png">
            </a>
        </div>
    </div>    
</template>


<style scoped>
.ps-header-bg{
    width: 100%;
    background: url("../assets/icons/ps-section-bg-02.jpg") no-repeat center center fixed;
    background-size: cover;
    height: 100vh;
    opacity: 0.9;
}

.ps-header-logo{
    width: 50px;
    height: 50px;
    border-radius: 50px;
    margin-top: 20px;
    margin-left: 50px
}

img:hover{
    text-decoration: none;
    color: #34ebc3;
    box-shadow: 8px 8px 20px 5px #34ebc3;
}
</style>