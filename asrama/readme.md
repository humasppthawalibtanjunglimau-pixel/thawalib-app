<!doctype html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Asrama - Thawalib Tanjung Limau</title>
<meta name="description" content="Info Asrama, Aturan, dan Jadwal Asrama Pondok Pesantren Thawalib Tanjung Limau" />
<style>
  :root{
    --bg1:#082f26; --bg2:#0b5f46; --gold:#f6c85f;
    --card: rgba(255,255,255,0.04);
    --glass: rgba(255,255,255,0.03);
    --muted: rgba(255,255,255,0.9);
    --radius:14px;
  }
  *{box-sizing:border-box}
  body{
    margin:0; font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, Arial;
    min-height:100vh;
    background: linear-gradient(160deg,var(--bg1) 0%, var(--bg2) 60%);
    color:var(--muted); -webkit-font-smoothing:antialiased;
    padding:24px;
  }

  .wrap{ max-width:1100px; margin:0 auto; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border-radius:18px; padding:20px; border:1px solid rgba(255,255,255,0.04); box-shadow:0 12px 40px rgba(2,6,23,0.55); }

  header{ display:flex; gap:16px; align-items:center; }
  .logo{ width:90px; height:90px; padding:8px; background:rgba(255,255,255,0.02); border-radius:12px; border:1px solid rgba(255,255,255,0.04); object-fit:contain; }
  h1{ margin:0; font-size:22px; color:var(--gold) }
  p.lead{ margin:4px 0 0 0; color:rgba(255,255,255,0.9) }

  .hero{ margin-top:16px; display:flex; gap:18px; align-items:center; padding:14px; border-radius:12px; background:linear-gradient(90deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.03); }
  .hero .left{ flex:1 }
  .hero h2{ margin:0; font-size:18px; color:var(--gold) }
  .hero p{ margin:6px 0 0 0; font-size:14px }

  .grid{ display:grid; grid-template-columns: 1fr 360px; gap:18px; margin-top:18px; }
  @media (max-width:980px){ .grid{ grid-template-columns:1fr } }

  /* Main cards */
  .card{ background:var(--card); padding:14px; border-radius:12px; border:1px solid rgba(255,255,255,0.03); }
  .section-title{ font-weight:700; color:var(--gold); margin-bottom:10px }

  /* rules list */
  .rules{ list-style:decimal; padding-left:18px; color:rgba(255,255,255,0.92); line-height:1.6; margin:0 }
  .rules li{ margin:8px 0 }

  /* schedule table */
  table{ width:100%; border-collapse:collapse; margin-top:10px; font-size:14px; background:rgba(255,255,255,0.03); border-radius:8px; overflow:hidden; }
  th, td{ padding:10px 12px; text-align:left; border-bottom:1px solid rgba(255,255,255,0.03) }
  th{ background:rgba(0,0,0,0.12); color:var(--gold) }

  /* sidebar */
  .sidebar .card{ margin-bottom:12px }
  .badge{ display:inline-block; padding:6px 10px; background:var(--gold); color:#083426; border-radius:10px; font-weight:700; font-size:13px }

  /* collapsible details */
  details{ background:rgba(255,255,255,0.02); padding:10px; border-radius:10px; margin-bottom:10px; border:1px solid rgba(255,255,255,0.03) }
  details summary{ cursor:pointer; font-weight:600; color:var(--gold); outline:none }
  details[open]{ box-shadow:0 8px 28px rgba(0,0,0,0.35) }

  /* actions */
  .actions{ display:flex; gap:10px; margin-top:12px; flex-wrap:wrap }
  .btn{ display:inline-block; padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:700; color:#082f26; background:var(--gold); border:0 }
  .btn.secondary{ background:transparent; color:var(--muted); border:1px solid rgba(255,255,255,0.06) }

  /* back */
  .back{ display:inline-block; margin-top:18px; color:var(--gold); text-decoration:none; font-weight:700 }

  /* small note */
  .note{ font-size:13px; color:rgba(255,255,255,0.85); margin-top:8px }
</style>
</head>
<body>
  <div class="wrap" role="main" aria-labelledby="asrama-title">

    <header>
      <img src="../img/logo-thawalib.png" alt="Logo Thawalib" class="logo">
      <div>
        <h1 id="asrama-title">Info Asrama — Thawalib Tanjung Limau</h1>
        <p class="lead">Informasi singkat, aturan asrama, dan jadwal harian santri</p>
      </div>
      <div style="margin-left:auto; text-align:right">
        <div class="badge">Asrama • Teratur & Nyaman</div>
        <div style="font-size:13px; color:rgba(255,255,255,0.85); margin-top:8px">Kontak: <a href="https://wa.me/085274042328" style="color:var(--gold); text-decoration:underline">0852-7404-2328</a></div>
      </div>
    </header>

    <section class="hero" aria-hidden="false">
      <div class="left">
        <h2>Asrama Kami — Tempat Pembinaan & Kedisiplinan</h2>
        <p>
          Asrama Thawalib dirancang untuk mendukung aktivitas ibadah, belajar kitab,
          dan membangun karakter santri. Lingkungan aman, teratur, dan penuh bimbingan.
        </p>

        <div class="actions">
          <a class="btn" href="../ppdb/index.html">Info PPDB</a>
          <a class="btn secondary" href="../galeri/readme.md">Lihat Foto Asrama</a>
        </div>
      </div>

      <div style="width:220px; text-align:center">
        <img src="../img/logo-kaligrafi.png" alt="Logo kecil" style="width:140px; border-radius:10px; border:1px solid rgba(255,255,255,0.04); padding:8px; background:rgba(255,255,255,0.01)">
        <div class="note">Asrama putra & putri terpisah — pembinaan khusus oleh ustadz/ustadzah</div>
      </div>
    </section>

    <div class="grid" role="region" aria-label="Konten Asrama">

      <main>
        <div class="card" aria-labelledby="info-title">
          <div class="section-title" id="info-title">Informasi Asrama</div>
          <p>
            Asrama Thawalib menampung santri dengan fasilitas tidur teratur, ruang belajar malam,
            area wudhu & masjid kecil di dalam area asrama. Setiap asrama memiliki pembina
            dan jadwal piket yang jelas.
          </p>

          <details>
            <summary>Fasilitas Asrama</summary>
            <ul style="margin:10px 0 0 18px; color:rgba(255,255,255,0.9)">
              <li>Ranjang susun & lemari per santri</li>
              <li>Ruang baca & belajar malam</li>
              <li>Ruang Makan & dapur teratur</li>
              <li>Area olahraga kecil</li>
            </ul>
          </details>

          <details>
            <summary>Pembina & Kontak</summary>
            <div style="margin-top:10px; color:rgba(255,255,255,0.9)">
              <strong>Pembina Asrama Putra:</strong> Ust. Ahmad (WA: 0852-xxxx-xxxx)<br>
              <strong> Pembina Asrama Putri:</strong> Ustadzah Siti (WA: 0852-xxxx-xxxx)
            </div>
          </details>

        </div>

        <div class="card" aria-labelledby="rules-title" style="margin-top:14px">
          <div class="section-title" id="rules-title">Aturan Asrama (Ringkasan)</div>
          <ol class="rules">
            <li>Wajib hadir di apel pagi & pemanggilan shalat berjamaah.</li>
            <li>Patuh pada jadwal belajar malam (qiyam & halaqah).</li>
            <li>Menjaga kebersihan ruangan & area umum.</li>
            <li>Tidak boleh membawa barang terlarang; serahkan barang elektronik sesuai aturan.</li>
            <li>Gunakan bahasa yang sopan dengan teman & pembina.</li>
            <li>Laporkan gangguan kesehatan ke pembina segera.</li>
          </ol>

          <p class="note">Catatan: Aturan lengkap tersedia di buku asrama. Pelanggaran akan diberi sanksi sesuai ketentuan pondok.</p>
        </div>

        <div class="card" aria-labelledby="jadwal-title" style="margin-top:14px">
          <div class="section-title" id="jadwal-title">Jadwal Harian (Contoh)</div>

          <table aria-label="Jadwal Harian Asrama">
            <thead>
              <tr><th>Waktu</th><th>Kegiatan</th></tr>
            </thead>
            <tbody>
              <tr><td>04:00 - 04:40</td><td>Bangun & Tahajud / Persiapan Subuh</td></tr>
              <tr><td>04:40 - 05:30</td><td>Shalat Subuh berjamaah & Tilawah</td></tr>
              <tr><td>05:30 - 06:30</td><td>Belajar Pagi / Kajian</td></tr>
              <tr><td>06:30 - 07:30</td><td>Sarapan & Persiapan Sekolah</td></tr>
              <tr><td>07:30 - 14:30</td><td>Kegiatan Akademik (Sekolah)</td></tr>
              <tr><td>15:00 - 16:30</td><td>Waktu Belajar Mandiri</td></tr>
              <tr><td>18:00 - 19:00</td><td>Shalat Maghrib & Makan</td></tr>
              <tr><td>20:00 - 22:00</td><td>Belajar Malam / Halaqah</td></tr>
              <tr><td>22:30</td><td>Persiapan tidur & istirahat</td></tr>
            </tbody>
          </table>

          <p class="note">Jadwal dapat berubah saat ada kegiatan khusus. Cetak jadwal lengkap di papan pengumuman asrama.</p>
        </div>
      </main>

      <aside class="sidebar">
        <div class="card">
          <div class="section-title">Pengumuman Singkat</div>
          <ul style="padding-left:18px; margin:8px 0; color:rgba(255,255,255,0.92)">
            <li>Piket umum: sekali seminggu, cek daftar di papan.</li>
            <li>Check kesehatan: setiap Senin & Kamis.</li>
            <li>Latihan kebersihan: tiap Jumat pagi.</li>
          </ul>

          <a class="btn" href="../pages/readme.md" style="margin-top:8px; display:inline-block">Info Lengkap</a>
        </div>

        <div class="card">
          <div class="section-title">Formulir & Dokumen</div>
          <p style="margin:0 0 10px 0; color:rgba(255,255,255,0.9)">Unduh formulir perlengkapan santri & tata tertib asrama.</p>
          <a class="btn secondary" href="../data/readme.md">Download</a>
        </div>

        <div class="card">
          <div class="section-title">Kontak Darurat</div>
          <p style="margin:0 0 6px 0; color:rgba(255,255,255,0.9)"><strong>Satpam:</strong> 0852-xxxx-xxxx</p>
          <p style="margin:0; color:rgba(255,255,255,0.9)"><strong>Bendahara:</strong> 0852-xxxx-xxxx</p>
        </div>
      </aside>

    </div>

    <a class="back" href="../index.html">← Kembali ke Beranda</a>
  </div>

  <script>
    // Progressive enhancement: ensure details keyboard accessible fallback
    document.querySelectorAll('details').forEach(d=>{
      d.addEventListener('keydown', (e)=>{
        if(e.key === 'Enter' || e.key === ' '){
          e.preventDefault();
          d.open = !d.open;
        }
      });
    });
  </script>
</body>
</html>

