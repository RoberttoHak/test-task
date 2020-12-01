<template>
    <header id="header" class="header">
         <div class="sign_up d-flex justify-content-center align-items-center">
                 <span>Sign up for our newsletter and receive 15% off your first scent purchase!</span>
         </div>

         <nav class="navbar navbar-expand-lg navbar-light ">

             <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                 <span class="navbar-toggler-icon"></span>
             </button>
             <div class="collapse navbar-collapse" id="navbarSupportedContent">

                 <div class="col-xl-4 col-lg-6">
                     <ul class="navbar-nav mr-auto text-uppercase">
                         <li class="nav-item">
                             <a class="nav-link" href="#">about us <span class="sr-only">(current)</span></a>
                         </li>
                         <li class="nav-item">
                             <a class="nav-link" href="#">our wines</a>
                         </li>
                         <li class="nav-item">
                             <a class="nav-link" href="#">where to find us <span class="sr-only">(current)</span></a>
                         </li>
                         <li class="nav-item">
                             <a class="nav-link" href="#">WILD CRUST BAKERY</a>
                         </li>
                         <li class="nav-item">
                             <a class="nav-link" href="#">contact us</a>
                         </li>
                     </ul>
                 </div>
                 <div class="col-xl-4 col-lg-3 d-flex justify-content-center">
                     <img src="../assets/logo.png" alt="logo">
                 </div>
                 <div class="col-xl-4 col-lg-3 d-flex justify-content-end">
                     <form class="form-inline my-2 my-lg-0">
                         <ul class="list-inline header_icon">
                             <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-search icon_header" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                 <path fill-rule="evenodd" d="M10.442 10.442a1 1 0 0 1 1.415 0l3.85 3.85a1 1 0 0 1-1.414 1.415l-3.85-3.85a1 1 0 0 1 0-1.415z"/>
                                 <path fill-rule="evenodd" d="M6.5 12a5.5 5.5 0 1 0 0-11 5.5 5.5 0 0 0 0 11zM13 6.5a6.5 6.5 0 1 1-13 0 6.5 6.5 0 0 1 13 0z"/>
                             </svg>
                             <svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-bag" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
                                 <path fill-rule="evenodd" d="M8 1a2.5 2.5 0 0 0-2.5 2.5V4h5v-.5A2.5 2.5 0 0 0 8 1zm3.5 3v-.5a3.5 3.5 0 1 0-7 0V4H1v10a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V4h-3.5zM2 5v9a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V5H2z"/>
                             </svg>
                         </ul>
                     </form>
                 </div>

             </div>
         </nav>
        <div class="backgroun_image">
            <div class="col text-center  image_text">
                <h1 class="logo_title">PHILIP LOBLEY WINES</h1>
                <h3 class="logo_subtitle">YEA VALLEY</h3>
                <button type="button" class="">SHOP NOW</button>
            </div>

        </div>

    </header>
</template>

<script>
  export default {
    name: "Header"
  }
</script>

<style scoped>
    .sign_up{
        background-color: #f2f2ea;
        box-sizing: content-box;
        width: 100%;
        height: 40px;
        padding:18px 0px 19px 0px;
    }
    .sign_up span{
        font-family: Neuzeit Grotesk;
        font-style: normal;
        font-weight: 300;
        font-size: 14px;
        line-height: 16px;
        /* identical to box height */
        text-align: center;

    }

    .header_icon{
        margin-top: 20px;
    }

    .header_icon a {
        color: #39383a !important;
    }
    .header a {
        font-family: Neuzeit Grotesk;
        font-style: normal;
        font-weight: 300;
        font-size: 13px;
        line-height: 15px;
        /* identical to box height */

        text-align: center;

        color: #3F3F3F;
    }
    .icon_header{
        margin-right: 20px;
    }

    .backgroun_image{
        background: url("../assets\/Rectangle.jpg") ;
        height: 845px;
        background-size: cover;
        background-position: center center;
        background-repeat: no-repeat;
    }

    .image_text{

    }

    .logo_title{
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 64px;
        line-height: 75px;
        /* identical to box height */
        padding-top: 470px;
        text-align: center;

        color: #FFFFFF;
    }
    .logo_subtitle{
        font-family: Roboto;
        font-style: normal;
        font-weight: 300;
        font-size: 36px;
        line-height: 42px;
        text-align: center;
        letter-spacing: 0.1em;
        margin-bottom: 87px;
        color: #FFFFFF;
    }
    .image_text button{
        padding: 17px 41px;
        background: #FFFFFF;
        font-family: Roboto;
        font-style: normal;
        font-weight: normal;
        font-size: 13px;
        line-height: 15px;
        text-align: center;
        border: none;
        margin-bottom: 122px;
        /* #1D1C1E */

        color: #1D1C1E;
    }
    @media only screen and  (max-width: 1500px) {

        .header a{
            margin: 0px;
        }
    }

</style>