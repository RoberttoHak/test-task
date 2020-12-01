<template>
  <section class="about_us">
    <div class="container-fluid">
      <div >
          <h4>About Us</h4>
          <p class="desc">Our family has owned the Glenburn property since 1992 and began planting in 1995 when Philip Lobley Wines was established. We are a small family run vineyard in the Yea valley, which produces about 1000 cases of boutique wines per year.</p>
          <div class="wine_images">
              <div class="row ">
                  <div class="col-lg-6 col-md-12 left_wine">
                      <div class="card bg-dark text-white border-none border-0">
                          <img class="card-img" src="../assets/wine_1.jpg" alt="wine_left">
                          <div class="card-img-overlay ">
                              <div class="card_text ">
                                  <p class="card-title">Philip Lobley Temptation Pinot Noir Yea Valley 2017</p>
                                  <span >$30.00</span>
                              </div>
                          </div>

                      </div>
                  </div>
                  <div class="col-lg-6 col-md-12">
                      <div class="card bg-dark text-white border-0">
                          <img class="card-img" src="../assets/wine_2.jpg" alt="wine_left">

                      </div>
                  </div>

                  <div class="col-lg-6 col-md-12 buttons_space">
                      <div class="row">
                          <div class="col-6 pr-2"><button type="button" class="btn btn-block quick_shop">QUICKSHOP</button></div>
                          <div class="col-6 pl-2"><button type="button" class="btn btn-block add_to_cart">ADD TO CART</button></div>
                      </div>


                  </div>


              </div>

          </div>

      </div>
    </div>
  </section>

</template>

<script>
export default {
  name: 'Home',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .about_us h4{
    margin-top: 64px;
    margin-bottom: 20px;
    font-family: Libre Franklin;
    font-style: normal;
    font-weight: 500;
    font-size: 28px;
    line-height: 34px;
    /* identical to box height */

    text-align: center;

    /* #1D1C1E */

    color: #1D1C1E;
  }
  .about_us .desc{
    max-width: 656px;
    margin: 0 auto 160px auto;
    font-family: Neuzeit Grotesk;
    font-style: normal;
    font-weight: 300;
    font-size: 15px;
    line-height: 150%;
    /* or 22px */

    text-align: center;

    /* #1D1C1E */

    color: rgba(0,0,0,.5);
  }

  .wine_images{
    margin:0 160px ;
  }

  .card_text{
    background: #4A454B;
    padding-left: 17px;
  }

  .card_text p{
      font-family: Libre Franklin;
      font-style: normal;
      font-weight: 500;
      font-size: 18px;
      line-height: 150%;
      display: block;
      /* identical to box height, or 27px */


      color: #FFFFFF;
  }
  .card_text span{
      font-family: Neuzeit Grotesk;
      font-style: normal;
      font-weight: 300;
      font-size: 14px;
      line-height: 150%;
      /* identical to box height, or 21px */
      color: #FFFFFF;
  }


   .card-img-overlay{
      padding: 0px !important;
      top: calc(100% - 63px);
  }

  .buttons_space{
      margin-top: 24px;
  }

  .quick_shop{
      /*margin-right: 13px;*/
      /*padding: 11px 129px;*/
      font-family: Neuzeit Grotesk;
      font-style: normal;
      font-weight: 300;
      font-size: 12px;
      line-height: 150%;
      /* identical to box height, or 18px */
      border-radius: 0px !important;
      text-align: center;
      letter-spacing: 0.1em;

      /* #1D1C1E */

      color: #1D1C1E;
  }

  .add_to_cart{
      /*padding: 11px 124px;*/
      font-family: Neuzeit Grotesk;
      font-style: normal;
      font-weight: 300;
      font-size: 12px;
      line-height: 150%;
      /* identical to box height, or 18px */
      border-radius: 0px !important;
      text-align: center;
      letter-spacing: 0.1em;

      /* #1D1C1E */

      color: #1D1C1E;
      background: #4A454B;
  }

  @media only screen and  (max-width: 1200px) {
      /* For portrait layouts only */
      .card_text p {
          font-family: Libre Franklin;
          font-style: normal;
          font-weight: 500;
          font-size: 14px;
          line-height: 150%;
          display: block;
          color: #FFFFFF;
      }
  }

  @media only screen and  (max-width: 990px) {
      /* For portrait layouts only */
      .about_us .desc{
          max-width: 100%;
      }
      .wine_images{
          margin: 0 10px;
      }
  }
</style>
