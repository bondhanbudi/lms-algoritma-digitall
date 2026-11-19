# 🎓 Bondan Academy – LMS Algoritma Digital Marketing

LMS interaktif berbasis web untuk siswa SMK Jurusan Bisnis Digital: materi, game simulasi, kuis HOTS, dan sertifikat digital.

## Fitur
- **Beranda & Profil** – nama/kelas tersimpan otomatis (localStorage), dashboard progres, lencana.
- **Materi Interaktif** – konsep dasar algoritma, Machine Learning (5 manfaat), dan 7 platform media sosial.
- **Game "Social Algo Master"** – 5 skenario, 2 keputusan strategis per skenario, grafik metrik beranimasi.
- **Kuis HOTS** – 10 soal pilihan ganda (A–E) dengan pembahasan otomatis.
- **Sertifikat & Laporan** – unduh laporan nilai dan sertifikat dalam satu berkas `.html`.

## Teknologi
Satu berkas `index.html` (React 18, Tailwind CSS, Babel Standalone, Lucide Icons via CDN). Tanpa build, tanpa server.

## Cara menjalankan lokal
Buka `index.html` di Chrome/Edge (perlu internet untuk memuat CDN).

## Cara hosting di GitHub Pages
1. Buat repositori baru di GitHub (mis. `bondan-academy-lms`), set **Public**.
2. Unggah seluruh isi folder ini (`index.html`, `README.md`, `.nojekyll`) ke cabang `main`.
   - Lewat web: **Add file → Upload files**, seret berkas, lalu **Commit changes**.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, lalu **Save**.
5. Tunggu 1–2 menit. Alamat LMS: `https://USERNAME.github.io/bondan-academy-lms/`

## Catatan
- Progres siswa tersimpan di browser masing-masing (localStorage), bukan di server.
- Untuk mengubah soal kuis atau skenario game, edit konstanta `QZ` dan `SC` di dalam `index.html`.
- Sumber materi: modul ajar "Memahami Algoritma Digital Marketing".
