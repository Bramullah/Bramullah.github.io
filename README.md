<!DOCTYPE html>
<html>
<head>
  <title>Food Gallery</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
    }

    /* Home Page */
    .home-page {
      background-color: #1d7cc4;
      padding: 45px;
      text-align: center;
    }

    /* Slideshow */
    .slideshow-container {
      max-width: 1000px;
      position:static;
      margin:auto;
      margin-top: 20px;
      text-align: center;
    }

    .slideshow-container img {
      max-width: 100%;
      max-height: 320px;
      width: auto;
      height: auto;
      object-fit: contain;
    }
    

    /* Cafe Sections */
    .cafe-section {
      padding: 50px;
      background-color: #a4501487;
    }

    /* Divider */
    .divider {
      height: 1px;
      background-color: #843030;
      margin: 20px 0;
    }

    /* Additional Information */
    .additional-info {
      padding: 50px;
      background-color: #adadad;
    }

    /* Information Columns */
    .info-columns {
      display: flex;
      justify-content: space-between;
    }

    .column {
      flex-basis: 30%;
    }

    /* Back to Home Button */
    .back-button {
      font-size: 16px;
      color: #333;
      background-color: #ddd;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .back-button:hover {
      background-color: #11a33d;
    }
  </style>
</head>
<body>
  <!-- Home Page -->
  <div class="home-page">
    <h1>Welcome to Food Gallery</h1>
    <p>Define your own imagination and create your own world</p>

    <div class="button-container">
      <a class="button" href="cafe1.html">Cafe 1</a>
      <a> | </a>
      <a class="button" href="cafe2.html">Cafe 2</a>
      <a> | </a>
      <a class="button" href="foodtruck.html">Food Truck</a>
      <a> | </a>
      <a class="button" href="warungmakan.html">Warung Makan</a>
      <a> | </a>
      <a class="button" href="comingsoon.html">Coming Soon</a>
    </div>
  </div>

  <!-- Slideshow -->
  <div class="slideshow-container">
    <div class="my-slides">
      <img src="https://interiordesign.id/wp-content/uploads/2023/01/06-6-Inspirasi-Desain-Cafe-Outdoor-Unik-1024x576.jpg" alt="Slide 1">
    </div> 
    <div class="my-slides">
      <img src="https://img.freepik.com/premium-vector/monochrome-rough-sketch-european-outdoor-sidewalk-cafe-restaurant-coffeehouse_198278-3876.jpg" alt="Slide 2">
    </div>

    <div class="my-slides">  
      <img src="https://www.pexels.com/photo/851555/download/" alt="Slide 3">
    </div>
    <div class="my-slides">
      <img src="https://cdn.pixabay.com/photo/2013/11/28/11/30/coffee-shop-220225_1280.jpg" alt="Slide 4">
    </div>

    <div class="my-slides">
      <img src="https://blog.amartha.com/wp-content/uploads/2021/01/food-truck.jpg" alt="Slide 5">
    </div>
    <div class="my-slides">
      <img src="https://legistra.id/wp-content/uploads/2018/12/food-truck-industry-trends-for-2017-1024x560.jpg" alt="Slide 6">
    </div>

    <div class="my-slides">
        <img src="https://jakarta.go.id/uploads/contents/content--20210323024308.jpg" alt="Slide 7">
      </div>
    <div class="my-slides">
        <img src="https://totabuan.news/wp-content/uploads/2021/09/ilustrasi-restoran-leko.jpg" alt="Slide 8">
    </div>  
  


    </div>
  <div class="divider"></div>

  <!-- Cafe 1 Section -->
  <div class="cafe-section">
    <h2>Cafe 1</h2>
    <img src="https://cove-blog-id.sgp1.cdn.digitaloceanspaces.com/cove-blog-id/2022/10/cafe-di-jaksel.webp" alt="Cafe 1">
    <p>Description of Cafe 1...</p>
  </div>
  <div class="divider"></div>

  <!-- Cafe 2 Section -->
  <div class="cafe-section">
    <h2>Cafe 2</h2>
    <img src="https://cdn.idntimes.com/content-images/post/20221206/unnamed-1-874faa3d0c500ec5df4a068aee93630e.jpg" alt="Cafe 2">
    <p>Description of Cafe 2...</p>
  </div>
  <div class="divider"></div>

  <!-- Food Truck Section -->
  <div class="cafe-section">
    <h2>Food Truck</h2>
    <img src="https://www.bfi.co.id/Blog/Blog%20New/Usaha%20food%20truck/Tips%20Usaha%20Food%20Truck.jpg" alt="Food Truck">
    <p>Description of Food Truck...</p>
  </div>
  <div class="divider"></div>

  <!-- Warung Makan Section -->
  <div class="cafe-section">
    <h2>Warung Makan</h2>
    <img src="https://media-cdn.tripadvisor.com/media/photo-s/16/28/90/02/pecel-lele-mas-iwan.jpg" alt="Warung Makan">
    <p>Description of the restaurant...</p>
  </div>
  <div class="divider"></div>

  <!-- Coming Soon Section -->
  <div class="cafe-section">
    <h2>Coming Soon</h2>
    <img src="https://img.freepik.com/free-vector/coming-soon-background-with-focus-light-effect-design_1017-27277.jpg" alt="Coming Soon">
    <p>BRB, Coming Soon!!</p>
    <p>Cant wait for anymore stuff that we gonna bring for you? Stay tuned!</p>
  </div>
  <div class="divider"></div>

  <!-- Additional Information -->
  <div class="additional-info">
    <h2>Additional Information</h2>
    <div class="info-columns">
      <div class="column">
        <h3>Pages</h3>
        <ul>
          <!-- <li><a href="index.html">Home</a></li> -->
          <li><a href="cafe1.html">Cafe 1</a></li>
          <li><a href="cafe2.html">Cafe 2</a></li>
          <li><a href="foodtruck.html">Food Truck</a></li>
          <li><a href="warungmakan.html">Warung Makan</a></li>
          <li><a href="about.html">About Us</a></li>
          <li><a href="comingsoon.html">Coming Soon!!</a></li>
        </ul>
      </div>
      <div class="column">
        <h3>Social</h3>
        <ul>
          <li><a href="https://www.instagram.com/bramullah">Instagram</a></li>
          <li><a href="https://www.linkedin.com/in/bramullah/">LinkedIn</a></li>
          <!-- Add more social links as needed -->
        </ul>
      </div>
      <div class="column">
        <h3>Contact</h3>
        <ul>
          <li>Email: info@example.com</li>
          <li>Phone: +62-123-456</li>
          <!-- Add more contact information as needed -->
        </ul>
      </div>
    </div>
  </div>

  <script>
    var slideIndex = 0;
    showSlides();

    function showSlides() {
      var slides = document.getElementsByClassName("my-slides");
      for (var i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
      }
      slideIndex++;
      if (slideIndex > slides.length) {
        slideIndex = 1;
      }
      slides[slideIndex - 1].style.display = "block";
      setTimeout(showSlides, 2000); // Change slide every 2 seconds
    }
  </script>
</body>
</html>
