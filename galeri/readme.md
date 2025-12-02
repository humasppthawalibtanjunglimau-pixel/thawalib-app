<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Galeri | Pondok Pesantren Thawalib Tanjung Limau</title>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(135deg, #0f5132, #198754, #d4af37);
        color: white;
    }

    header {
        text-align: center;
        padding: 40px 20px;
        background: rgba(0, 0, 0, 0.2);
        backdrop-filter: blur(3px);
    }

    header h1 {
        font-size: 2.4rem;
        margin-bottom: 10px;
        font-weight: 700;
        color: #d4f8d4;
    }

    header p {
        font-size: 1.1rem;
    }

    .container {
        max-width: 1100px;
        margin: 40px auto;
        padding: 20px;
    }

    h2 {
        border-left: 5px solid gold;
        padding-left: 10px;
        margin-bottom: 20px;
        font-size: 1.8rem;
    }

    /* GRID GALERI */
    .gallery-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
        gap: 15px;
    }

    .gallery-grid img {
        width: 100%;
        border-radius: 12px;
        cursor: pointer;
        transition: 0.3s;
        border: 3px solid rgba(255, 255, 255, 0.3);
    }

    .gallery-grid img:hover {
        transform: scale(1.05);
        border-color: gold;
    }

    /* LIGHTBOX */
    #lightbox {
        display: none;
        position: fixed;
        inset: 0;
        background: rgba(0, 0, 0, 0.85);
        justify-content: center;
        align-items: center;
        z-index: 999;
    }

    #lightbox img {
        max-width: 90%;
        max-height: 90%;
        border-radius: 10px;
        border: 4px solid gold;
    }

    #lightbox:target {
        display: flex;
    }

    /* VIDEO EMBED */
    .video-box {
        margin-top: 20px;
        border-radius: 15px;
        overflow: hidden;
        border: 4px solid gold;
        box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
    }

    iframe {
        width: 100%;
        height: 380px;
    }

    /* BUTTON BACK */
    .back-btn {
        display: inline-block;
        margin-top: 40px;
        padding: 12px 25px;
        background: gold;
        color: black;
        font-weight: bold;
        border-radius: 8px;
        text-decoration: none;
        transition: 0.3s;
    }

    .back-btn:hover {
        background: white;
        color: green;
    }

</style>
</head>

<body>

<header>
    <h1>Galeri Kegiatan Pondok</h1>
    <p>Dokumentasi Foto & Video Santri – Pondok Pesantren Thawalib Tanjung Limau</p>
</header>

<div class="container">

    <h2>📸 Foto Kegiatan</h2>

    <div class="gallery-grid">
        <a href="#img1"><img src="../img/sample1.jpg" alt="Kegiatan Santri"></a>
        <a href="#img2"><img src="../img/sample2.jpg" alt="Kegiatan Pondok"></a>
        <a href="#img3"><img src="../img/sample3.jpg" alt="Acara Pondok"></a>
        <a href="#img4"><img src="../img/sample4.jpg" alt="Belajar Santri"></a>
        <a href="#img5"><img src="../img/sample5.jpg" alt="Kegiatan Asrama"></a>
        <a href="#img6"><img src="../img/sample6.jpg" alt="Upacara Pondok"></a>
    </div>

    <!-- LIGHTBOX PREVIEW -->
    <div id="img1" class="lightbox"><a href="#"><img src="../img/sample1.jpg"></a></div>
    <div id="img2" class="lightbox"><a href="#"><img src="../img/sample2.jpg"></a></div>
    <div id="img3" class="lightbox"><a href="#"><img src="../img/sample3.jpg"></a></div>
    <div id="img4" class="lightbox"><a href="#"><img src="../img/sample4.jpg"></a></div>
    <div id="img5" class="lightbox"><a href="#"><img src="../img/sample5.jpg"></a></div>
    <div id="img6" class="lightbox"><a href="#"><img src="../img/sample6.jpg"></a></div>

    <h2>🎥 Video Kegiatan</h2>

    <div class="video-box">
        <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
            title="Video Kegiatan Pondok"></iframe>
    </div>

    <a href="../index.html" class="back-btn">⬅ Kembali ke Beranda</a>

</div>

</body>
</html>

