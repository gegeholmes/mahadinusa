# Hotel Jungutbatu — Nusa Lembongan

Situs statis sederhana untuk Hotel Jungutbatu (Desa Jungutbatu, Pulau Nusa Lembongan).

Isi:
- `index.html` — halaman utama (bahasa Indonesia)
- `styles.css` — gaya dasar
- `assets/` — gambar hero, kamar, dan kolam renang (disimpan lokal)

Preview lokal

1. Jalankan server statis dari folder repo:

```bash
python3 -m http.server 8000
```

2. Buka di browser:

http://localhost:8000/index.html

Commit & push

```bash
git add .
git commit -m "Add static site for Hotel Jungutbatu with local assets and README"
# git push origin main
```

Catatan

- Gambar diunduh dari Unsplash untuk preview. Jika ingin menggunakan gambar milik sendiri, ganti file di `assets/`.
- Mau saya bantu `git push` dan setup GitHub Pages? Beri tahu saya jika iya.
