<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link href="https://fonts.googleapis.com/css2?family=Odibee+Sans&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
    <style>
      
      /* Style for navbar-1  */
      
      #navbar-1 {
        display: flex;
        align-items: center;
        justify-content: space-around;
        background-color: #f5f5f5;
        margin-left: 10px;
      }

      #links {
        text-align: center;
        padding-bottom: 10px;
        flex-direction: column;
      }

      .logo, .logo, .logo {
        height: 40px;
        width: 40px;
      }

      .margin {
        padding-left: 50px;
        padding-right: 50px;
      }

      #links a {
        text-decoration: none;
        color: rgb(40, 40, 40);
      }

      /* Style for navbar-2  */

      #navbar-2 {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding-top: 10px;
        padding-bottom: 10px;
      }
      .logo-2 {
        height: 20px;
        width: 20px;
        margin-left: 10px;
      }

      #navbar-2-logo,
      #navbar-2-links,
      #search-links {
        width: 33%;
      }

      #navbar-2-links a {
        text-decoration: none;
        color: black;
        margin-left: 10px;
        margin-right: 10px;
        font-size: large;
      }

      #search-links {
        display: flex;
        justify-content: flex-end;
        align-items: center;
      }

      #search {
        height: 30px;
        border-radius: 15px;
        padding-right: 20px;
        padding-left: 20px;
        font-size: 15px;
      }

      /* Navbar-3 */
      
      #navbar-3 {
        display: flex;
        align-items: center;
        flex-direction: column;
        background-color: #f5f5f5;
        padding: 10px;
      }
      #navbar-3 h4,
      #navbar-3 h6 {
        margin: 0;
      }

      /* Image cards */

      #image-cards {
        display: flex;
        justify-content: space-between;
      }

      #image-cards img {
        width: 32%;
        border-radius: 15px;
        border: 1px solid gray;
      }

      /* Additional text */

      #additional-text {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-top: 30px;
      }

      .button{
        color: white;
      }

      .small-text,
      .big-text {
        margin: 0;
        padding: 5px;
      }

      .big-text {
        font-size: 50px;
        font-weight: bold;
      }

      #additional-text button {
        border-radius: 20px;
        margin-top: 15px;
        padding: 10px 20px 10px 20px;
        font-size: 15px;
        background-color: rgb(20, 20, 20);
        color: white;
      }

      #slider-frame{
        margin-top: 100px;
      }

      .slide-images{
        margin-top: 50px;
      }

      #footer-box-1{
        width: 70%;
        margin: 40px auto;
        display: flex;
        justify-content: space-around;
      }

      /* footer box - 2 */
      #footer-box-2 {
        display: flex;
        justify-content: space-between;
        padding: 20px;
        background-color: black;
        color: white;
      }

      .box-1 {
        width: 50%;
        display: flex;
        justify-content: space-around;
      }

      .box-2 img {
        margin: 0 10px;
        width: 30px;
      }

      .grey {
        font-size: small;
        color: gray;
      }

      .box-3 {
        display: flex;
        justify-content: space-around;
        color: white;
        background-color: black;
        padding: 0 40px;
      }

      .box-3 div {
        display: flex;
        justify-content: space-between;
      }

      .box-3 div img {
        width: 20px;
        height: 20px;
  
      }

      .container-1, 
      .container-2 {
        width: 20px;
      }

      .box-3-text{ color: gray;
        font-size: small;

      }
    </style>
    <title>Document</title>
  </head>
  <body>

    <!-- Navbar - 1 -->

    <div id="navbar-1" class="margin">
      <img src="images/jordanlogo.jpg" class="logo" />
      <div id="navbar-1" class="margin">
        <img src="https://brandslogos.com/wp-content/uploads/thumbs/adidas-logo-vector.svg" class="logo" />
    </div>
      </div>
    <div>
      <div id="links">
        <a href="">Help |</a>
        <a href="">Join Us |</a>
        <a href="">Sign In</a>
      </div>
    </div>

    <!-- Navbar-2 -->

    <div id="navbar-2" class="margin">
      <div id="navbar-2-logo">
        <h4>Stripe&Swoosh</h4>
      </div>
      <div id="navbar-2-links">
        <a href="">Men</a>
        <a href="">Women</a>
        <a href="">Kids</a>
        <a href="">Sale</a>
        <a href="">SNKRS</a>
      </div>
      <div id="search-links">
        <input type="text" id="search" placeholder="search" />
        <img
          src="https://cdn-icons-png.flaticon.com/128/1077/1077035.png"
          class="logo-2"
        />
        <img
          src="https://cdn-icons-png.flaticon.com/128/1656/1656850.png"
          class="logo-2"
        />
      </div>
    </div>

    <!-- Navbar-3 -->

    <div id="navbar-3" class="margin">
      <h4>Stripes Swoosh Hustle </h4>
      <h6>Free Delivery</h6>
    </div>

    <!-- Image Cards -->
    <div id="image-cards" class="margin">
      <img src="images2/j2.jpg" />
      <img src="images2/travis.png" />
      <img src="images2/tatum.jpg" />
    </div>

    <!-- Additional text -->

    <div id="additional-text">
      <p class="small-text">The ACG guide to</p>
      <h1 class="big-text">FIND YOUR STYLE</h1>
      <p class="small-text">
        The first 50 years were just the beginning. Watch our 50th anniversary
        file, directed by and starring lee and indigo Hubbard-Salk.
      </p>
      <button>
        <a href="page1.html" style="color: white"
        >Shop</a></button>
    </div>

    <!-- Slide -->

    <link rel="stylesheet" href="style2.css" />
    <link
      rel="stylesheet"
    />
  <body>
    <div class="slider-frame">
      <div class="slide-images">
        <div class="img-container"
        data-bs-interval="3500">
          <img src="images2/lebron-carousel.jpg" />
        </div>
        <div class="img-container">
          <img src="images2/kd---15.jpeg" />
        </div>
            <div class="img-container">
              <img src="images2/kobe---11.jpeg" />
            </div>
      </div>
    </div>
  </body>

  <!-- Image Cards - 2 -->

  <div id="image-cards" class="margin">
    <img src="https://footwearnews.com/wp-content/uploads/2016/07/rita-ora-summer-2016-shoes-style-28.jpg?w=683" />
    <img src="https://www.instyle.com/thmb/vAlum7LloBIWZJH-UpaUlBVSMkc=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/083122-LOTD-Jennifer-Lawrence-lead-2000-d345d68c20d24f5ca900ea32ad3720c3.jpg" />
    <img src="https://s.yimg.com/ny/api/res/1.2/HszrwJxtYKlPW5EppNoyCg--/YXBwaWQ9aGlnaGxhbmRlcjt3PTY0MDtoPTk5MA--/https://media.zenfs.com/en/footwear_news_642/539f58d2ec934d8615bead6313e13c9e" />
  </div>

  <!-- Additional text -->

  <div id="additional-text">
    <p class="small-text">The ACG guide to</p>
    <h1 class="big-text">FIND YOUR SLIDES</h1>
    <p class="small-text">
      'Impossible is Nothing' is not a tagline for us. By being optimistic and knowing the power of sport, we see endless possibilities to apply this power and push all people forward with action.
    </p>
    <button>
      <a href="page2.html" style="color: white"
      >Shop</a></button>
  </div>

  <!-- Slide - 2 -->

  <link rel="stylesheet" href="style2.css" />
  <link
    rel="stylesheet"
  />
<body>
  <div class="slider-frame">
    <div class="slide-images">
      <div class="img-container"
      data-bs-interval="3500">
        <img src="https://cdn.shopify.com/s/files/1/0245/0866/1806/products/F355401-Edited.png?v=1665018391" />
      </div>
      <div class="img-container">
        <img src="https://i.ebayimg.com/images/g/ml4AAOSwnA1g6zkQ/s-l1600.png" />
      </div>
          <div class="img-container">
            <img src="https://images.squarespace-cdn.com/content/v1/532313ece4b08487acaec7a2/fccd1b12-09b0-4e52-8486-2246b22b6cb1/adidas-originals-adilette-22-alumin-alumin-alumin-gx6950-sneaker-packshots-180.png?format=1000w" />
          </div>
    </div>
  </div>
</body>

  <!-- Footer box -->

  <div id="footer-box-1">
    <div>
      <h4>Mens Shoes</h4>
      <p>Mens Lifestyle</p>
      <p>All Mens Shoes</p>
      <p>Mens running Shoes</p>
      <p>Mens Football shoes</p>
    </div>
    <div>
      <h4>Womens shoes</h4>
      <p>Womens Lifestyle</p>
      <p>All Womens Shoes</p>
      <p>Womens running Shoes</p>
      <p>womens Football shoes</p>
    </div>
    <div>
      <h4>Kids shoes</h4>
      <p>Kids Lifestyle</p>
      <p>All Kids Shoes</p>
      <p>Kids running Shoes</p>
      <p>Kids Football shoes</p>
    </div>
    <div><h4>Adventure shoes</h4>
      <p>Outdoor Lifestyle</p>
      <p>Hiking Shoes</p>
      <p>Trek Shoes</p>
      <p>Climbing shoes</p>
    </div>
  </div>

  <!-- Footer box - 2 -->

  <div id="footer-box-2">
    <div class="box-1">
      <div>
        <h4>Find a store</h4>
        <h4>Become a member</h4>
        <h4>Sign up</h4>
        <h4>Student Discount</h4>
        <h4>Send Us Feedback</h4>
      </div>
      <div>
        <h4>Get Help</h4>
      <p class="grey">Order Status</p>
      <p class="grey">Delivery</p>
      <p class="grey">Returns</p>
      <p class="grey">Payment Option</p>
      <p class="grey">Contact Us</p>
      </div>
      <div>
        <h4>About Stripes&Swoosh</h4>
      <p class="grey">News</p>
      <p class="grey">Careers</p>
      <p class="grey">Investors</p>
      <p class="grey">Sustainability</p>
    </div>
    </div>
    <div class="box-2">
      <img src="https://cdn-icons-png.flaticon.com/128/145/145802.png" alt="facebook" />
      <img src="https://cdn-icons-png.flaticon.com/128/3955/3955024.png" alt="instagram" />
      <img src="https://cdn-icons-png.flaticon.com/128/3670/3670151.png" alt="twitter" />
  </div>
  </div>
  <div class="box-3">
    <div class="container-1">
      <img src="https://cdn-icons-png.flaticon.com/128/684/684908.png" 
      alt="pin-location" />
      <p class="box-3-text">Philippines</p>
      <p class="box-3-text">Stripes&Swoosh, Inc. All Rights Reserved</p>
    </div>
    <div class="container-2">
      <p class="box-3-text">Guides</p>
      <p class="box-3-text">Terms of Service</p>
      <p class="box-3-text">Privacy Policy</p>
      <p class="box-3-text">Terms of sale</p>
    </div>
  </div>
  </body>
</html>

<!-- <html>
  <head>
       <title>

       </title>
  </head>
  <body>
    
  </body>
</html> -->
