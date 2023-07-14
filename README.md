<!DOCTYPE html>
<html>
<head>
  <title>Optimal Location for Café</title>
  <style>

    /* Body Page */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    /* Home Page */
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    /* Main Page */
    main {
      padding: 40px;
      text-align: center;
    }

    /* SlideShow */
    .slideshow-container {
      max-width: 1000px;
      position: static;
      margin: auto;
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

    /* Button */
    .buttons-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 50px;
    }

    .btn {
      background-color: #fff;
      border: 2px solid #1b4169;
      color: #ffffff;
      padding: 45px 165px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      position: relative;
      z-index: 1;
      font-size: 24px;
    }

    .btn:before {
      content: "";
      background-size: cover;
      background-position: center;
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      z-index: -1;
    }

    .btn-indoor:before {
      background-image: url("https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8Y2FmZXxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80");
    }

    .btn-outdoor:before {
      background-image: url("https://awsimages.detik.net.id/community/media/visual/2022/06/26/cafe-di-makassar-yang-mengusung-konsep-taman_169.jpeg?w=650&q=80");
    }

    /* Devider */
    .divider {
      width: 100%;
      height: 2px;
      background-color: #ccc;
      margin-top: 50px;
      margin-bottom: 30px;
    }

    /* Additional Info */
    .additional-info {
      text-align: center;
      font-size: 20px;
      color: #888;
    }
    
    .lower-font {
      font-size: 15px;
    }

    .left-font {
      text-align: left;
      font-size: 15px;
    }

    /* Footer */
    footer {
      background-color: #f9f9f9;
      padding: 10px;
      text-align: center;
      font-size: 12px;
      color: #888;
    }
  </style>
</head>


<body>
  <header>
    <!-- Home Page -->
    <h1>Welcome to Café Location Guide</h1>
    <p>Define your own imagination and create your own world</p>
    <p></p>
    <p></p>
  </header>

  <main>

    <!-- Slideshow -->
    <div class="slideshow-container">

      <!-- Indoor Photo -->
          <!-- Design / Sketch Photo (1-3)-->
      <div class="my-slides">
        <img src="https://media.istockphoto.com/id/1188407275/vector/cafe-interior-graphic-black-white-sketch-illustration-vector.jpg?s=612x612&w=0&k=20&c=hWJ0eC_IFGOXi3oDiVw7eYgeEzllXGickS712kYtFUs=" alt="Slide 1">
      </div>
      <div class="my-slides">
        <img src="https://media.istockphoto.com/id/1361006405/vector/cafe-bar-graphic-black-white-interior-sketch-illustration-vector.jpg?s=612x612&w=0&k=20&c=YamrRLfotfW4aL3HVJnncSQQHQOejzbJu7OnZwW-p-s=" alt="Slide 2">
      </div> 
      <div class="my-slides">
        <img src="https://previews.123rf.com/images/aluna1/aluna12002/aluna1200200059/140617214-cafe-interior-bar-graphic-black-white-sketch-illustration-vector.jpg" alt="Slide 3">
      </div>  

          <!-- Real Photo (4-6)-->
      <div class="my-slides">
        <img src="https://modifico.id/blog/wp-content/uploads/2022/11/Desain-interior-kafe-low-budget.jpg" alt="Slide 4">
      </div>
      <div class="my-slides">
        <img src="https://cdn-cms.pgimgs.com/static/2019/05/Cafe-Industrial-Foto-Utama.jpg" alt="Slide 5">
      </div>
      <div class="my-slides">
        <img src="https://www.pinhome.id/info-area/wp-content/uploads/2022/02/Hario-Cafe-1024x680.jpg" alt="Slide 6">
      </div> 

      <!-- Outdoor Photo -->
          <!-- Design / Sketch Photo (7-9)-->
      <div class="my-slides">  
        <img src="https://img.freepik.com/premium-vector/monochrome-rough-sketch-european-outdoor-sidewalk-cafe-restaurant-coffeehouse_198278-3876.jpg" alt="Slide 7">
      </div>
      <div class="my-slides">  
        <img src="https://i2-prod.leicestermercury.co.uk/incoming/article8256878.ece/ALTERNATES/s615/0_muscafe.jpg" alt="Slide 8">
      </div>
      <div class="my-slides">  
        <img src="https://media.gettyimages.com/id/1141500852/vector/trendy-fast-food.jpg?s=612x612&w=gi&k=20&c=DktYNLSVFKxHJrL6iiwo0QbLpM4KkpemcNH4QCKSfRM=" alt="Slide 9">
      </div>

          <!-- Real Photo (10-12)-->
      <div class="my-slides">
        <img src="https://interiordesign.id/wp-content/uploads/2023/01/06-6-Inspirasi-Desain-Cafe-Outdoor-Unik-1024x576.jpg" alt="Slide 10">
      </div>
      <div class="my-slides">
        <img src="https://cdn-2.tstatic.net/wartakota/foto/bank/images/suasana-outdoor-di-lumida-cafe.jpg" alt="Slide 11">
      </div>
      <div class="my-slides">
        <img src="https://i0.wp.com/media.dekoruma.com/article/2019/01/11150646/44eeb1dfc5ae35498faff502348f5050.jpg?resize=750%2C1000&ssl=1" alt="Slide 12">
      </div>

    </div>
    <!-- End of Slideshow -->

    <div class="divider"></div>

    <!-- Button Indoor / Outdoor -->
    <div class="buttons-container">
      <a href="https://ibramullah.github.io" class="btn btn-indoor">Indoor Café</a>
      <a href="outdoor.html" class="btn btn-outdoor">Outdoor Café</a>
    </div>

    <div class="divider"></div>

    <!-- Additional Info -->
    <div class="additional-info">
      <p>Discover the perfect café location for your business!</p>
      <p class="lower-font">Café Location Guide adalah platform komprehensif yang dirancang untuk membantu pemilik kafe dalam menentukan lokasi optimal untuk bisnis mereka di Jakarta Selatan. Kami memanfaatkan kekuatan pemikiran analitis untuk memberikan wawasan dan panduan berharga untuk membuka ruang kafe dalam dan luar ruangan.</p>
      <p class="lower-font">Platform kami dirancang khusus untuk pengusaha di industri makanan dan minuman, dengan fokus pada segmen kafe. Kami memahami pentingnya memilih lokasi yang tepat untuk memaksimalkan kesuksesan usaha kafe Anda. Dengan menggunakan pemikiran analitis, kami bertujuan untuk membantu pemilik kafe membuat keputusan yang tepat tentang penataan kafe mereka di dalam atau di luar ruangan di Jakarta Selatan.</p>
      <p></p>
      <p class="left-font">Apa yang kita tawarkan:</p>
      <ul class="left-font">
        <li>Analisis Lokasi: Kami menawarkan analisis lokasi terperinci, dengan mempertimbangkan faktor-faktor seperti lalu lintas pejalan kaki, demografi, persaingan, dan tren lokal. Pendekatan analitis kami membantu Anda mengevaluasi kelayakan dan potensi membuka kafe indoor atau outdoor di area tertentu di Jakarta Selatan.</li>
        <li>Wawasan Komparatif: Kami memberikan analisis komparatif tentang kelebihan dan kekurangan ruang kafe indoor dan outdoor. Dengan memahami manfaat dan pertimbangan unik dari setiap opsi, Anda dapat membuat keputusan berdasarkan informasi yang selaras dengan visi kafe dan audiens target Anda.</li>
        <li>Evaluasi Sumber Daya: Platform kami menawarkan wawasan tentang sumber daya dan bahan yang diperlukan untuk menyiapkan kafe dalam atau luar ruangan. Kami menguraikan peralatan, furnitur, dan elemen penting lainnya yang diperlukan untuk setiap jenis pengaturan kafe, memungkinkan Anda untuk merencanakan dan mempersiapkannya dengan tepat.</li>
        <li>Lingkungan Sekitar: Selain mengevaluasi ruang interior atau eksterior kafe, kami mempertimbangkan lingkungan sekitar. Kami menganalisis lingkungan sekitar, objek wisata terdekat, aksesibilitas, dan faktor lain yang dapat memengaruhi kesuksesan kafe Anda. Memahami konteks lokal sangat penting untuk menentukan lokasi kafe yang optimal di Jakarta Selatan.</li>
      </ul>
      <p></p>
      <p class="lower-font">Dengan Panduan Lokasi Kafe, Anda dapat membuat keputusan berdasarkan data dan membuka potensi penuh bisnis kafe Anda. Kami berkomitmen untuk membantu pemilik kafe dalam perjalanan mereka menemukan lokasi yang ideal untuk kafe indoor atau outdoor mereka di Jakarta Selatan, menggunakan pemikiran analitis sebagai landasan platform kami.</p>
    </div>
  </main>

  <footer>
    <p>&copy; 2023 Café Location Guide. All rights reserved.</p>
  </footer>

  <!-- SlideShowScript -->
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
