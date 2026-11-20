# Panduan Redeploy Chi Nho Nha Coffee ke Netlify

## Opsi A — Via GitHub (Disarankan agar Netlify Functions tetap aktif)
1. Ekstrak file ZIP ini.
2. Salin seluruh isi folder `Chi-Nho-Nha-main/` (termasuk folder `images/`, `index.html`, `robots.txt`, `sitemap.xml`, `llms.txt`, `netlify.toml`, `netlify/`, `package.json`, `favicon.png`, dan `googlee1dc9a219964ef24.html`) ke repositori GitHub `fikrisrgr/Chi-Nho-Nha`.
3. Commit & push ke branch `main`. Netlify akan otomatis melakukan redeploy.

## Setelah Deploy Selesai
1. Pastikan `https://chinhonhacoffee.netlify.app/robots.txt`, `/sitemap.xml`, `/llms.txt`, dan `/images/hero.jpg` terbuka normal.
2. Masuk ke **Google Search Console**, kirimkan `https://chinhonhacoffee.netlify.app/sitemap.xml`, lalu klik **URL Inspection → Request Indexing** pada URL utama.
3. Uji URL beranda di **Google Rich Results Test** (`https://search.google.com/test/rich-results`).
