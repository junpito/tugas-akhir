# Skripsi: Penerapan Attention U-Net untuk Segmentasi Mikrovaskular pada Whole Slide Image Jaringan Ginjal Manusia

Repositori ini berisi dokumen LaTeX untuk penyusunan skripsi saya sebagai mahasiswa S1 Data Science di Institut Teknologi Sumatera.

## 📌 Abstrak Singkat
Penelitian ini membahas penerapan arsitektur Attention U-Net untuk melakukan segmentasi mikrovaskular pada citra histologi jaringan ginjal manusia. Model diimplementasikan menggunakan TensorFlow dan menunjukkan peningkatan performa dibandingkan U-Net standar berdasarkan metrik Dice Score dan IoU.

## 🗂️ Struktur Folder
.
├── bab/ # Bab-bab skripsi (Bab 1–5)
├── abstrak/ # File abstrak dan metadata
├── gambar/ # Gambar, ilustrasi, dan hasil segmentasi
├── pustaka/ # Referensi tambahan jika ada
├── lainnya/ # Data pendukung, lampiran, dsb.
├── daftar-pustaka.bib # File referensi BibTeX
├── gaya.cls # Template LaTeX dari institusi
├── main.tex # Main file untuk kompilasi skripsi
└── README.md # File ini

## 🛠️ Cara Kompilasi

1. Install LaTeX distribution seperti:
   - **TeX Live** (Linux, Windows)
   - **MiKTeX** (Windows)
   - **Overleaf** (online)

2. Kompilasi secara lokal (opsional):
   
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex

## Hasil pdf
Berikut adalah versi full skripsi ini: - [Junpito Salim, 120450086](https://zenodo.org/records/15487180?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImY5NjE1ODQ4LWZkZmQtNDc4My1iZjk1LTlmZGEzYTY0MTgwZiIsImRhdGEiOnt9LCJyYW5kb20iOiJhZjA0YTMwZGU4YzhmOGEwOTU1YThiYTIyZTIyMDA2ZCJ9.-wjVCnYH_ljwnXciOvTnW1rwEjSDrSSPH76eZTvfbi_lWaHusDgcm3Swlwpm8-TjfGXQgaDznf-E-_D2zcdXiQ)

## Ucapan Terima Kasih dan Referensi

Terima kasih banyak kepada beberapa sumber yang menginspirasi penulis untuk membuat template ini, yaitu

- [B201 Telematics Laboratory, ITS](https://github.com/b201lab/template-buku-ta-its)
- [Template LaTeX IF Itera](https://github.com/josestg/Latex-TA-IF-ITERA)
- [Template LaTeX SAP Itera](https://www.overleaf.com/project/6163a7c46c2d4fec909aa54f)
- [Panduan Tugas Akhir SD Itera](https://sd.itera.ac.id/tugas-akhir/)
- []
## Lisensi

Kode sumber yang ada pada repositori ini dilisensikan di bawah [lisensi MIT](./LICENSE).