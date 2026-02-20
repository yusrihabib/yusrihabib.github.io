
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muhammad Yusri Habib</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif; }
    body { background:#000; color:#fff; scroll-behavior:smooth; }
    a { text-decoration:none; color:inherit; }

    header {
      position:fixed; top:0; width:100%; z-index:10;
      padding:20px 60px;
      display:flex; justify-content:space-between; align-items:center;
      background:rgba(0,0,0,0.6); backdrop-filter:blur(8px);
      border-bottom:1px solid #222;
    }

    header h1 span { color:#e10600; }
    nav a { margin-left:32px; opacity:0.7; }
    nav a:hover { opacity:1; color:#e10600; }

    .hero {
      height:100vh;
      display:flex; flex-direction:column; justify-content:center;
      padding:0 60px;
      background:linear-gradient(180deg,rgba(0,0,0,.3),#000), url('https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f') center/cover;
    }

    .hero h2 { font-size:60px; line-height:1.2; max-width:700px; }
    .hero h2 span { color:#e10600; }
    .hero p { max-width:520px; opacity:.75; margin:24px 0 40px; }

    .btn {
      padding:14px 34px; border:2px solid #e10600;
      color:#e10600; font-weight:600; width:fit-content;
      transition:.3s;
    }
    .btn:hover { background:#e10600; color:#000; }

    section { padding:100px 60px; }
    .section-title {
      font-size:34px; margin-bottom:48px;
      border-left:5px solid #e10600; padding-left:18px;
    }

    .gallery {
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
      gap:32px;
    }

    .video-card {
      background:#111; padding:14px; border-radius:12px;
      transition:.3s; box-shadow:0 10px 30px rgba(0,0,0,.4);
    }
    .video-card:hover { transform:translateY(-6px); }

    .video-card iframe {
      width:100%; height:200px; border-radius:8px; border:none;
    }

    .video-card h4 { margin-top:14px; font-weight:500; }

    .contact { max-width:520px; }

    footer {
      padding:40px 60px; border-top:1px solid #222;
      opacity:.6; font-size:14px; text-align:center;
    }

    @media(max-width:768px){
      header, .hero, section, footer { padding:24px; }
      .hero h2 { font-size:40px; }
      nav { display:none; }
    }
  </style>
</head>
<body>

<header>
  <h1>Yusri<span>Habib</span></h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#galeri">Galeri</a>
    <a href="#kontak">Kontak</a>
  </nav>
</header>

<div class="hero" id="home">
  <h2>Muhammad <span>Yusri</span><br>Habib Portfolio</h2>
  <p>hallo Saya Muhammad Yusri Habib, videografer profesional yang aktif sejak tahun 2020. Berpengalaman menangani berbagai proyek seperti wedding, prewedding, after movie, dan video angkatan sekolah, saya menghadirkan karya dengan pendekatan visual yang elegan, storytelling yang kuat, dan perhatian tinggi pada setiap detail. Setiap video dirancang untuk tidak hanya merekam momen, tetapi menghidupkan kembali cerita dan emosi di dalamnya.</p>
  <a class="btn" href="https://wa.me/6287833372219" target="_blank">WhatsApp Sekarang</a>
</div>

<section id="galeri">
  <h3 class="section-title">Video Project</h3>
  <div class="gallery">

    <!-- GOOGLE DRIVE VIDEO -->
    <div class="video-card">
      <iframe src="https://drive.google.com/file/d/1D6z2SX1VzEjxvMrJzXJUVnjK3ZKJWQBS/view" allow="autoplay"></iframe>
      <h4>Highlight video wedding</h4>
    </div>

    <div class="video-card">
      <iframe src="https://drive.google.com/file/d/1cgSbSUK36N0EUrrTvUYnumgykw7814PY/view"></iframe>
      <h4>highlight video wedding</h4>
    </div>
<div class="video-card">
  <iframe 
    src="https://drive.google.com/file/d/1D6z2SX1VzEjxvMrJzXJUVnjK3ZKJWQBS/preview"
    allow="autoplay">
  </iframe>
  <h4>Wedding Cinematic</h4>
</div>

    <div class="video-card">
      <iframe src="https://drive.google.com/file/d/FILE_ID/preview"></iframe>
      <h4>After Movie</h4>
    </div>

  </div>
</section>

<section id="kontak">
  <h3 class="section-title">Kontak</h3>
  <div class="contact">
    <p>Siap berkolaborasi? Hubungi saya langsung melalui WhatsApp untuk diskusi project.</p><br>
    <a class="btn" href="https://wa.me/6287833372219" target="_blank">Chat WhatsApp</a>
  </div>
</section>

<footer>
  © 2026 Portofolio Muhammad Yusri · All Rights Reserved
</footer>

</body>
</html>
