# RANGE//PROTOCOL

Aim trainer & sens lab 3D bergaya Valorant — jalan langsung di browser, satu file, tanpa install, tanpa server.

**Fitur:**

- **Tes Serius** — benchmark 4 blok (Flick 30 · Micro 20 · Peek 16 · Tracking 45 dtk) → AIM SCORE 0–100 + grade S–D, diagnosa kelemahan presisi (overshoot/undershoot, asimetri kiri-kanan, bias vertikal, reaksi, recovery), rekomendasi sens, dan kartu skor PNG buat dibagi.
- **Cari Sens Otomatis** — metode PSA (Perfect Sensitivity Approximation) versi terukur: 7 ronde flick, sens diganti diam-diam tiap ronde, konvergen ±5% ke sens yang bikin flick-mu mendarat pas. Dinilai dari pengukuran gerakan mouse, bukan perasaan.
- **Latihan Bebas** — drill endless: Flick, Micro, Peek duel, Strafe tracking.
- **Rasa Valorant** — FOV 103°, matematika sens asli (0,07°/count), hitbox kepala 1-tap, spray full-auto dengan bloom, suara tembakan/dink headshot/kill beruntun (disintesis, tanpa file audio), damage number.
- **Replay & laporan** — semua gerakan mouse direkam per milidetik; ekspor JSON/teks buat dianalisis (misalnya sama Claude).

**Cara pakai:** buka situsnya (atau file `index.html`) di Chrome/Edge → isi sens Valorant kamu → pilih mode. Raw input aktif otomatis lewat pointer lock. `F` = fullscreen, `ESC` = pause. DPI ga dibutuhin — bisa diisi opsional di layar hasil kalau mau lihat eDPI/cm-360.

**Deploy sendiri:**

- **Vercel:** import repo ini di [vercel.com/new](https://vercel.com/new) → framework "Other" → Deploy. Selesai (ini situs statis, gratis, ga ada beban server — semua jalan di browser pemain).
- **GitHub Pages:** Settings → Pages → Source: branch `main`, folder `/` → Save.

**Catatan:** proyek fan-made buat latihan, tidak berafiliasi dengan Riot Games. Dibuat bareng Claude.
