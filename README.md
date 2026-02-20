<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Muhammad Yusri Habib | Videographer</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
    body{background:#000;color:#fff;line-height:1.7}
    a{text-decoration:none;color:inherit}

    header{position:fixed;top:0;width:100%;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:20px 60px;background:rgba(0,0,0,.6);backdrop-filter:blur(10px);border-bottom:1px solid #222}
    header h1 span{color:#e10600}
    nav a{margin-left:32px;opacity:.7}
    nav a:hover{opacity:1;color:#e10600}

    .hero{
      height:100vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      padding:0 60px;
      background:linear-gradient(180deg,rgba(0,0,0,.55),#000),url('https://github.com/yusrihabib/yusrihabib.github.io/blob/main/IMG_0533.jpeg) center/cover fixed;
      background-position:60% 20%;
    }
    .hero h2{font-size:56px;max-width:760px;line-height:1.2}
    .hero h2 span{color:#e10600}
    .hero p{max-width:520px;opacity:.85;margin:24px 0 40px}

    .btn{padding:14px 36px;border:2px solid #e10600;color:#e10600;font-weight:600;width:fit-content;transition:.3s}
    .btn:hover{background:#e10600;color:#000}

    section{padding:110px 60px}
    .section-title{font-size:34px;margin-bottom:48px;border-left:5px solid #e10600;padding-left:18px}

    .about{max-width:760px;opacity:.85}

    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:32px}
    .video-card{background:#111;padding:20px;border-radius:14px;box-shadow:0 15px 40px rgba(0,0,0,.5);transition:.35s}
    .video-card:hover{transform:translateY(-8px)}
    .video-card iframe{width:100%;height:210px;border:none;border-radius:10px}
    .video-card h4{margin-top:14px;font-weight:500}
    .video-card p{opacity:.75;font-size:14px;margin-top:6px}

    footer{text-align:center;padding:40px 60px;border-top:1px solid #222;opacity:.6}

    @media(max-width:768px){
      header,.hero,section,footer{padding:24px}
      nav{display:none}
      .hero{background-position:50% 10%}
      .hero h2{font-size:36px}
    }

    .reveal{opacity:0;transform:translateY(40px);transition:1s ease}
    .reveal.active{opacity:1;transform:none}
  </style>
</head>
<body>

<header>
  <h1>Yusri<span>Habib</span></h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#why">Why Me</a>
    <a href="#works">Works</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero reveal" id="home">
  <h2>Mengabadikan <span>Cerita</span><br>dalam Visual Cinematic</h2>
  <p>Saya Muhammad Yusri Habib, videographer profesional sejak 2020 yang berfokus pada wedding, prewedding, after movie, dan video angkatan sekolah dengan pendekatan visual elegan dan berkelas.</p>
  <a class="btn" href="https://wa.me/6287833372219" target="_blank">Booking Sekarang</a>
</section>

<section class="reveal" id="about" style="background:linear-gradient(180deg,rgba(0,0,0,.85),rgba(0,0,0,.95)),url('https://drive.google.com/uc?id=1x3raU1UxaFBYCJ8yf7G1PpOjkTT4os9d') center/cover no-repeat;">
  <h3 class="section-title">About Me</h3>
  <p class="about"><strong>Muhammad Yusri Habib</strong> adalah videographer profesional yang aktif sejak 2020. Berpengalaman dalam produksi video wedding, prewedding, after movie, dan video angkatan sekolah dengan fokus pada storytelling, detail visual, dan emosi yang kuat.</p>
  <br>
  <p class="about"><strong>Pengalaman Profesional:</strong><br>
  • <strong>2020 – 2023</strong> · Freelance Videographer<br>
  • <strong>2024 – 2025</strong> · Videographer – Project by Historia<br>
  • <strong>2025 – 2026</strong> · Video Editor – Nesnumoto</p>
</section>

<section class="reveal" id="why">
  <h3 class="section-title">Why Choose Me</h3>
  <div class="gallery">
    <div class="video-card"><h4>🎬 Cinematic Storytelling</h4><p>Setiap video dibangun dengan alur cerita dan emosi.</p></div>
    <div class="video-card"><h4>💍 Wedding Specialist</h4><p>Fokus pada momen sakral pernikahan.</p></div>
    <div class="video-card"><h4>⏱️ Tepat Waktu</h4><p>Workflow rapi dan deadline terjaga.</p></div>
    <div class="video-card"><h4>🤝 Profesional</h4><p>Nyaman diajak kerja sama dari awal hingga akhir.</p></div>
  </div>
</section>

<section class="reveal" id="works">
  <h3 class="section-title">Selected Works</h3>
  <div class="gallery">
    <div class="video-card"><iframe src="https://drive.google.com/file/d/12NJvY-KtwI2h9wYU32mqf8HU3oW6XTet/preview"></iframe><h4>Highlight Wedding</h4></div>
    <div class="video-card"><iframe src="https://drive.google.com/file/d/1cgSbSUK36N0EUrrTvUYnumgykw7814PY/preview"></iframe><h4>Highlight Wedding</h4></div>
    <div class="video-card"><iframe src="https://drive.google.com/file/d/1D6z2SX1VzEjxvMrJzXJUVnjK3ZKJWQBS/preview"></iframe><h4>Highlight Wedding</h4></div>
    <div class="video-card"><iframe src="https://www.instagram.com/reel/DSpNczciZ1S/embed"></iframe><h4>After Movie</h4></div>
    <div class="video-card"><iframe src="https://www.youtube.com/embed/C-9LbpafXFA"></iframe><h4>After Movie</h4></div>
  </div>
</section>

<section class="reveal" id="contact">
  <h3 class="section-title">Contact</h3>
  <p>Tertarik bekerja sama atau ingin berdiskusi mengenai project video?</p><br>
  <a class="btn" href="https://wa.me/6287833372219" target="_blank">Hubungi via WhatsApp</a>
</section>

<footer>© 2026 Muhammad Yusri Habib · Videographer</footer>

<script>
  const reveals=document.querySelectorAll('.reveal');
  const observer=new IntersectionObserver(entries=>{
    entries.forEach(e=>{if(e.isIntersecting)e.target.classList.add('active')})
  },{threshold:.15});
  reveals.forEach(r=>observer.observe(r));

  window.addEventListener('scroll',()=>{
    const hero=document.querySelector('.hero');
    hero.style.backgroundPositionY=`${20+window.scrollY*0.05}%`;
  });
</script>
</body>
</html>
