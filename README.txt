# Selefrase

Website mobile untuk memparafrase berita bahasa Inggris menjadi artikel bahasa Indonesia.

## Cara buka di HP

Website ini harus di-hosting terlebih dahulu. Cara paling mudah:

### Opsi 1 — Netlify Drop
1. Buka https://app.netlify.com/drop
2. Drag & drop folder `selefrase_website`
3. Setelah upload selesai, Netlify akan memberi link website
4. Buka link tersebut dari HP

### Opsi 2 — Vercel
1. Upload folder ini ke GitHub
2. Buka Vercel
3. Import repository
4. Deploy
5. Buka link dari HP

## File utama
- `index.html` = website utama
- `manifest.json` = agar bisa ditambahkan ke Home Screen
- `service-worker.js` = cache dasar
- `icon.svg` = ikon aplikasi

## Catatan
Beberapa situs berita bisa memblokir pembacaan otomatis. Kalau gagal, paste isi artikel ke kolom "Teks Sumber yang Terbaca".
