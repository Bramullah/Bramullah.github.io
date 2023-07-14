<!DOCTYPE html>
<html>
<head>
  <title>Optimal Location for Café</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    main {
      padding: 40px;
      text-align: center;
    }

    .buttons-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 50px;
    }

    .btn {
      background-color: #fff;
      border: 2px solid #007bff;
      color: #466b92;
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

    .divider {
      width: 100%;
      height: 2px;
      background-color: #ccc;
      margin-top: 50px;
      margin-bottom: 30px;
    }

    .additional-info {
      text-align: center;
      font-size: 20px;
      color: #888;
    }
    
    .lower-font {
      font-size: 15px;
    }

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
    <h1>Welcome to Café Location Guide</h1>
  </header>

  <main>
    <div class="buttons-container">
      <a href="indoor.html" class="btn btn-indoor">Indoor Café</a>
      <a href="outdoor.html" class="btn btn-outdoor">Outdoor Café</a>
    </div>
    <div class="divider"></div>
    <div class="additional-info">
      <p>Discover the perfect café location for your business!</p>
      <p class="lower-font">Café Location Guide adalah platform komprehensif yang dirancang untuk membantu pemilik kafe dalam menentukan lokasi optimal untuk bisnis mereka di Jakarta Selatan. Kami memanfaatkan kekuatan pemikiran analitis untuk memberikan wawasan dan panduan berharga untuk membuka ruang kafe dalam dan luar ruangan.</p>
      <p class="lower-font">Platform kami dirancang khusus untuk pengusaha di industri makanan dan minuman, dengan fokus pada segmen kafe. Kami memahami pentingnya memilih lokasi yang tepat untuk memaksimalkan kesuksesan usaha kafe Anda. Dengan menggunakan pemikiran analitis, kami bertujuan untuk membantu pemilik kafe membuat keputusan yang tepat tentang penataan kafe mereka di dalam atau di luar ruangan di Jakarta Selatan.</p>
      <p class="lower-font">Apa yang kita tawarkan:</p>
      <ul class="lower-font">
        <li>Analisis Lokasi: Kami menawarkan analisis lokasi terperinci, dengan mempertimbangkan faktor-faktor seperti lalu lintas pejalan kaki, demografi, persaingan, dan tren lokal. Pendekatan analitis kami membantu Anda mengevaluasi kelayakan dan potensi membuka kafe indoor atau outdoor di area tertentu di Jakarta Selatan.</li>
        <li>Wawasan Komparatif: Kami memberikan analisis komparatif tentang kelebihan dan kekurangan ruang kafe indoor dan outdoor. Dengan memahami manfaat dan pertimbangan unik dari setiap opsi, Anda dapat membuat keputusan berdasarkan informasi yang selaras dengan visi kafe dan audiens target Anda.</li>
        <li>Evaluasi Sumber Daya: Platform kami menawarkan wawasan tentang sumber daya dan bahan yang diperlukan untuk menyiapkan kafe dalam atau luar ruangan. Kami menguraikan peralatan, furnitur, dan elemen penting lainnya yang diperlukan untuk setiap jenis pengaturan kafe, memungkinkan Anda untuk merencanakan dan mempersiapkannya dengan tepat.</li>
        <li>Lingkungan Sekitar: Selain mengevaluasi ruang interior atau eksterior kafe, kami mempertimbangkan lingkungan sekitar. Kami menganalisis lingkungan sekitar, objek wisata terdekat, aksesibilitas, dan faktor lain yang dapat memengaruhi kesuksesan kafe Anda. Memahami konteks lokal sangat penting untuk menentukan lokasi kafe yang optimal di Jakarta Selatan.</li>
      </ul>
      <p class="lower-font">Dengan Panduan Lokasi Kafe, Anda dapat membuat keputusan berdasarkan data dan membuka potensi penuh bisnis kafe Anda. Kami berkomitmen untuk membantu pemilik kafe dalam perjalanan mereka menemukan lokasi yang ideal untuk kafe indoor atau outdoor mereka di Jakarta Selatan, menggunakan pemikiran analitis sebagai landasan platform kami.</p>
    </div>
  </main>

  <footer>
    <p>&copy; 2023 Café Location Guide. All rights reserved.</p>
  </footer>
</body>
</html>
