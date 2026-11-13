# Farabi Akil Azra — Creative Portfolio

Website portofolio statis menggunakan HTML, Bootstrap 5.3.8, dan custom CSS seperlunya. Project dapat dipublikasikan melalui GitHub Pages.

## Struktur project

- `index.html` — struktur dan konten halaman.
- `style.css` — custom styling untuk identitas visual, komposisi galeri, dekorasi, dan breakpoint khusus.
- `assets/` — gambar karya dan logo software.
- `assets/icon logo/` — logo Photoshop, Illustrator, Procreate, dan Canva dalam format SVG.

## Prinsip styling

- Gunakan utility Bootstrap untuk kebutuhan umum seperti flexbox, alignment, gap, dan layout sederhana.
- Pertahankan custom CSS untuk komposisi visual khusus yang tidak memiliki padanan Bootstrap langsung.
- Ukuran logo software dipertahankan pada 43 × 43 piksel.
- Hindari menambahkan aturan CSS baru apabila utility Bootstrap sudah mencukupi.

## Menjalankan secara lokal

Buka `index.html` di browser. Bootstrap CSS dan Google Fonts dimuat melalui CDN, sehingga koneksi internet diperlukan untuk memuat keduanya.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub.
2. Upload seluruh isi folder ini ke root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu klik **Save**.

## Pemeliharaan

- Ubah konten, alamat email, dan tautan sosial di `index.html`.
- Tambahkan aset baru ke folder `assets/` dan gunakan path relatif.
- Letakkan styling khusus yang benar-benar diperlukan di `style.css`.
