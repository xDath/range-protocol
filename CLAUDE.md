# Instruksi untuk Claude Code

Proyek ini situs statis: satu `index.html`, TANPA build step, tanpa dependency, tanpa server.

## Tugas deploy

1. Buat repo GitHub publik bernama `range-protocol` dari folder ini dan push.
2. Deploy ke Vercel production. Project name: `range-protocol`. Framework preset: **Other**. Build command: kosong. Output directory: `.` (root).

Kredensial `gh` dan `vercel` sudah terkonfigurasi di mesin ini.

## Perintah

```bash
git init -b main && git add -A && git commit -m "RANGE//PROTOCOL v3"
gh repo create range-protocol --public --source=. --push
vercel deploy --prod --yes
```

## Aturan

- JANGAN mengubah isi `index.html` (aplikasi sudah final & teruji — satu file utuh, semua inline).
- Jangan menambah framework, bundler, atau restrukturisasi apa pun.
- Setelah deploy, laporkan URL production-nya.
