# Warta Terkini - Astro Frontend

## Cara Setup Lokal

1. Masuk ke folder `main/`
2. Jalankan `npm install`
3. Jalankan `npm run dev`
4. Buka di browser: http://localhost:4321

## Deploy ke GitHub Pages

1. Pastikan sudah commit semua perubahan.
2. Jalankan:
   ```bash
   npm run deploy
   ```
3. Di GitHub, buka Settings > Pages, pilih branch `gh-pages` dan folder root (`/`).
4. Situs Anda akan tersedia di:  
   `https://TutiJong.github.io/AI-Quality/`

## Catatan
- Jika mengubah nama repo, edit juga `base` di `astro.config.mjs`
- Untuk domain kustom, tambahkan file `CNAME` di folder `main/public/` sesuai domain Anda.

## Fitur
- Fetch berita dari https://warta-terkini.com
- Filter kategori & pencarian berita
- Halaman detail berita
- Tampilan modern dengan Tailwind CSS
