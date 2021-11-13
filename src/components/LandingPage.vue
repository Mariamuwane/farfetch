<template>
<div id="landingPage">
  <div class="banner-container text-center flow-root bg-black p-2">
    <div class="swiper-banner"><span class="block text-white items-center px-4 py-2">Incoming |
      Shop the latest arrivals here</span></div>
  </div>
  <header class="p-6 mb-4 mt-5 overflow-hidden">
    <!-- Top navigation -->
<div class="topnav container">

  <!-- Centered link -->
  <div class="topnav-centered">
    <a href="#logo" class="active" style="font-weight: bolder; font-size: larger; font: outline;">FARFETCH</a>
  </div>

  <!-- Left-aligned links (default) -->
  <a href="#women">Women</a>
  <a href="#men">Men</a>
  <a href="#kids">Kids</a>


  <!-- Right-aligned links -->
  <div class="topnav-right mr-1">
    <i class="far fa-flag mr-1"> </i> <span class="ml-1"></span>
    <i class="far fa-user"> </i>&nbsp;
    <i class="far fa-star"> </i>&nbsp;
    <i class="fas fa-shopping-bag"> </i>&nbsp;
  </div>

</div>
    <div class="container">
      <div class="left">
        <p>Please select a gender to shop</p>
      </div>
      <div class="right">
        <form>
          <input type="search" placeholder="search">
          <button type="submit" class="fa fa-search h-14"></button>
        </form>
      </div>
    </div>
  </header>
  <main id="content" class="overflow-hidden container">
    <div>
      <div>
        <div class="row mt-5">
          <div class="returns col-4">
            <i class="fas fa-box"></i>
            Free returns with pick-up service
          </div>
          <div class="col-4">
            <i class="fas fa-truck"></i>
            Fast Shipping
          </div>
          <div class="col-4">
            <i class="fas fa-credit-card"></i>
            International click & collect
          </div>
        </div>
        <div class="row mt-5"> 
          <div class="col-6">
          <p :style="image" class=" image font-extrabold text-black-5xl text-center align-text-bottom">SHOP MEN</p>
          <img class="w-100 object-cover">
          </div>
          <div class="col-6">
          <p class="font-extrabold text-black-5xl text-center align-text-bottom">SHOP WOMEN</p>
          <img :src="womenPicture" class="w-100 object-cover">
          </div>
        </div>
      </div>
      <div class="container m-5">
        <div class="row">
          <div class="col-3">
            <div class="ft1">
              <span>
              <p>Featured designers for men</p>
              </span>
            </div>
            <div class="list1">
              <div>
                <p><a href="#">Comme Des Garçons Play</a></p>
                <p><a href="#">Brunello Cucinelli</a></p>
                <p><a href="#">TOM FORD Eyewear</a></p>
                <p><a href="#">Thom Browne</a></p>
                <p><a href="#">visvim</a></p>
                <p><a href="#">Buscemi</a></p>
                <p><a href="#">Raf Simons</a></p>
                <p><a href="#">Axel Arigato</a></p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="categ1">
              <span>
              <p>Top categories for men</p>
              </span>
            </div>
            <div class="list2">
              <div>
                <p><a href="#">Jordan Low-Tops</a></p>
                <p><a href="#">Off-White T-Shirts</a></p>
                <p><a href="#">Common Project Shoes</a></p>
                <p><a href="#">Fendi Belts</a></p>
                <p><a href="#">Rick Owen Shoes</a></p>
                <p><a href="#">Brioni Glasses and Frames</a></p>
                <p><a href="#">Versace Shirts</a></p>
                <p><a href="#">Palm Angels Hoodies</a></p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="ft2">
              <span>
              <p>Featured designers for women</p>
              </span>
            </div>
            <div class="list3">
              <div>
                <p><a href="#">Paris Texas</a></p>
                <p><a href="#">Canada Goose</a></p>
                <p><a href="#">Amina Muaddi</a></p>
                <p><a href="#">Self-Portrait</a></p>
                <p><a href="#">Amen</a></p>
                <p><a href="#">MCM</a></p>
                <p><a href="#">Stella McCartney</a></p>
                <p><a href="#">Issey Miyake</a></p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="categ2">
              <span>
              <p>Top categories for women</p>
              </span>
            </div>
            <div class="list4">
              <div>
                <p><a href="#">Gucci Belts</a></p>
                <p><a href="#">Zimmerman Skirts</a></p>
                <p><a href="#">Vivienne Westwood Jewelry</a></p>
                <p><a href="#">Gucci Fine Rings</a></p>
                <p><a href="#">Prada Shoulder Bags</a></p>
                <p><a href="#">Jimmy Choo Clutch Bags</a></p>
                <p><a href="#">Zimmerman Blouses</a></p>
                <p><a href="#">Isabel Marant Sneakers</a></p>
              </div>
            </div>
          </div>
        </div>
      </div>  
      <div class="text-center">
        <button class="flex items-center px-4 py-3 border rounded text-black-500 border-black-500 focus:outline">View More</button>
      </div>
      <div class="row container overflow-hidden">
        <div class="howTo col-4">
          <a class="hangIcon"></a>
          <p><a href="#">HOW TO SHOP</a></p>
          <p>Your guide to shopping and placing orders.</p>
        </div>
        <div class="FAQ col-4">
          <a class="queIcon"></a>
          <p><a href="#">FAQs</a></p>
          <p>Your Questions answered.</p>
        </div>
        <div class="contact col-4">
          <a class="chatIcon"></a>
          <p><a href="#">NEED HELP?</a></p>
          <p>Contact our global customer service team.</p>
        </div>
      </div>
    </div>
  </main>
  <div>
    <div class="signup w-full max-w-xs text-center bg-white shadow-md rounded flex">
      <h1 class="text-4xl lg:text-xl font-bold text-400 mb-2 lg:mb-6">SIGN UP AND GET 10% OFF</h1>
      <p>Sign up for early sale access, new in, promotions and more</p>
      <form class=" flex shadow-md rounded px-8 pt-6 pb-8 mb-4">
        <div class="gender space-y-4">
          <div class="gender-option flex items-start">
            <label>
              <input class="h-5 h-4 w-4 ml-3 text-sm mx-8 mr-1" type="radio">   Womenswear
            </label>
            <label>
              <input type="radio" class="mr-1 ml-4">  Menswear
            </label>
          </div>
        </div>
        <p class="">GET UPDATES BY</p>
        <div class="email">
          <label>
            <div class="checkbox">
              <input class="checked shadow border rounded focus:shadow-outline " type="checkbox" id="emailCheckbox">
              <use class="tickIcon"></use>
              Email
            </div>
          </label>
        </div>
        <div>
          <input type="email" placeholder="Your email address" class="block text-gray-700 text-sm font-bold mb-2" for="Your email address">

        </div>
        <div class="formControl">
          <label class="md:w-2/3 block text-gray-500 font-bold">
            <input type="checkbox" name="smsCheckbox" id="smsCheckbox" class="mr-2 leading-tight">
            <use id="smsIcon"></use> SMS
          </label><br>
          <button type="submit" class=" shadow bg-black 
          hover:bg-black focus:shadow-outline focus:outline-none text-white font-bold py-2 px-4 rounded mt-2">Sign up</button>
        </div><br>
        <p>By subscribing you agree with our Terms & Conditions<br> and Privacy Policy. 
          <span> To opt out, click unsubscribe at the <br>bottom of our emails</span></p>
      </form>
    </div>
  </div>
  <footer class="bg-black m-4 p-4">
    <section class="footer">
      <div class="container">
        <div class="row text-white">
          <div class="col-4">
            <h5>FARFETCH APP</h5>
            <span>Farfetch App for iOS and Android</span>
          </div>
          <div class="col-4">
            <h5>DESTINATION/REGION, CURRENCY AND LANGUAGE</h5>
            <div class="changeCountry">
              <div class="flagIcon"></div>
              <div>British Indian Ocean Territory,<span> USD $</span></div>
            </div>
            <div class="follow-us mt-30 mb-10">
              <div>
                <h5>FOLLOW US</h5>
              </div>
              <div class=" mr-1">
                <i class="fab fa-instagram mr-1"> </i> <span class="ml-1"></span>
                <i class="fab fa-facebook"> </i>&nbsp;
                <i class="fab fa-twitter"> </i>&nbsp;
                <i class="fab fa-snapchat"> </i>&nbsp;
                <i class="fab fa-pinterest"> </i>&nbsp;
                <i class="fab fa-youtube"> </i>&nbsp;

              </div>
            </div>
          </div>
          <div class="col-2">
            <h5>CUSTOMER SERVICE</h5>
            <div>
              <div class="list-none text-white">
                <p><a href="#">Help and contact us</a></p>
                <p><a href="#">Orders and shipping</a></p>
                <p><a href="#">Payment and pricing</a></p>
                <p><a href="#">returns and returns</a></p>
                <p><a href="#">FAQs</a></p>
                <p><a href="#">Terms and conditions</a></p>
                <p><a href="#">Privacy policy</a></p>
                <p><a href="#">Accessibility</a></p>
                
              </div>
            </div>
          </div>
          <div class="col-2">
            <h5>ABOUT FARFETCH</h5>
            <div>
              <div class="list-none text-white appearance-none">
                <p><a href="#">About us</a></p>
                <p><a href="#">Investors</a></p>
                <p><a href="#">FARFETCH boutique partners</a></p>
                <p><a href="#">Friend referral discount</a></p>
                <p><a href="#">Affiliate programme</a></p>
                <p><a href="#">Careers</a></p>
                <p><a href="#">FARFETCH customer promise</a></p>
                <p><a href="#">FARFETCH app</a></p>
                <p><a href="#">Sitemap</a></p>
                <p><a href="#">Positively FARFETCH</a></p>
              </div>
            </div>
          </div>
        </div>
        <div class="baseline">
          <span class="text-white">'FARFETCH' and the 'FARFETCH' logo are trade marks of FARFETCH UK Limited and are registered in numerous jurisdictions around the world.</span>
        </div>
        <div class="baseline">
          <span class="text-white">© Copyright 2021 FARFETCH UK Limited. All rights reserved.</span>
        </div>
      </div>
    </section>
  </footer>
</div>
</template>

<script>
export default {
  name: "LandingPage",
  data() {
    return {
      image: {'background-image':'url('+require('../assets/farfetch1.jpg')+')'},
      image2: {'background-image':'url('+require('../assets/farfetch2.webp')+')'},

      farfetch1: require('../assets/farfetch1.jpg'),
      womenPicture: require('../assets/farfetch2.webp')
    }
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css" scoped>
</style>
