<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profil Guru – Pondok Pesantren Thawalib Tanjung Limau</title>

    <style>
        body {
            margin: 0;
            font-family: "Poppins", sans-serif;
            background: linear-gradient(to bottom, #0e4937, #145c4f, #1c7a6a);
            color: white;
        }

        header {
            text-align: center;
            padding: 35px 20px;
            background: rgba(255,255,255,0.08);
            backdrop-filter: blur(4px);
        }

        .title {
            font-size: 32px;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .subtitle {
            font-size: 16px;
            opacity: 0.85;
        }

        .guru-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            padding: 30px;
        }

        .guru-card {
            background: rgba(255,255,255,0.12);
            border-radius: 18px;
            padding: 20px;
            text-align: center;
            backdrop-filter: blur(4px);
            transition: 0.3s;
        }

        .guru-card:hover {
            transform: translateY(-6px);
            background: rgba(255,255,255,0.18);
        }

        .guru-photo {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            background: white;
            margin: auto;
            margin-bottom: 12px;
            object-fit: cover;
            border: 4px solid #ffd86b;
        }

        .guru-name {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 5px;
        }

        .guru-role {
            font-size: 14px;
            opacity: 0.9;
            margin-bottom: 10px;
        }

        .guru-desc {
            font-size: 13px;
            opacity: 0.85;
        }

        .back-btn {
            display: block;
            margin: 40px auto;
            padding: 12px 26px;
            background: #ffd86b;
            color: #0e4937;
            text-decoration: none;
            font-weight: bold;
            font-size: 16px;
            border-radius: 10px;
            width: max-content;
            transition: 0.3s;
        }

        .back-btn:hover {
            background: #ffe9a9;
        }
    </style>
</head>

<body>

    <header>
        <div class="title">Profil & Data Tenaga Pengajar</div>
        <div class="subtitle">Pondok Pesantren Thawalib Tanjung Limau</div>
    </header>

    <section class="guru-container">

        <!-- GURU 1 -->
        <div class="guru-card">
            <img src="img/guru1.jpg" class="guru-photo">
            <div class="guru-name">Ust. Nama Guru 1</div>
            <div class="guru-role">Bidang Studi: Fiqih</div>
            <div class="guru-desc">
                Berpengalaman mengajar selama 10 tahun dan fokus pada pembinaan akhlak dan ibadah santri.
            </div>
        </div>

        <!-- GURU 2 -->
        <div class="guru-card">
            <img src="img/guru2.jpg" class="guru-photo">
            <div class="guru-name">Ustadzah Nama Guru 2</div>
            <div class="guru-role">Bidang Studi: Bahasa Arab</div>
            <div class="guru-desc">
                Mengembangkan metode pembelajaran bahasa Arab yang aktif & komunikatif.
            </div>
        </div>

        <!-- GURU 3 -->
        <div class="guru-card">
            <img src="img/guru3.jpg" class="guru-photo">
            <div class="guru-name">Ust. Nama Guru 3</div>
            <div class="guru-role">Bidang Studi: Al-Qur'an</div>
            <div class="guru-desc">
                Pembimbing tahfidz yang membantu santri meningkatkan kualitas hafalan.
            </div>
        </div>

        <!-- GURU 4 -->
        <div class="guru-card">
            <img src="img/guru4.jpg" class="guru-photo">
            <div class="guru-name">Ustadzah Nama Guru 4</div>
            <div class="guru-role">Bidang Studi: Matematika</div>
            <div class="guru-desc">
                Pendekatan pembelajaran yang mudah dipahami dan ramah santri.
            </div>
        </div>

        <!-- TAMBAH GURU LAIN DI SINI -->
    </section>

    <a class="back-btn" href="../index.html">⬅ Kembali ke Beranda</a>

</body>
</html>

