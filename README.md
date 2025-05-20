# 📄 Skripsi Dummy LaTeX - Contoh Dokumen Akademik

Repositori ini berisi contoh **skripsi dummy** (bukan skripsi asli) yang disusun sepenuhnya dengan **LaTeX**.  
Tujuannya adalah untuk memperkenalkan LaTeX sebagai alat penulisan dokumen ilmiah yang rapi, fleksibel, dan profesional khususnya untuk mahasiswa Indonesia.

## 🎯 Tujuan Proyek

- Memberikan referensi struktur skripsi lengkap dalam LaTeX
- Memperkenalkan fitur seperti: daftar isi otomatis, daftar pustaka BibTeX, margin skripsi sesuai standar
- Membantu mahasiswa atau siapa pun yang ingin belajar LaTeX dari contoh nyata

> ❗ Semua nama, isi, topik, dan data dalam skripsi ini **bersifat fiktif** dan tidak mewakili dokumen akademik asli.

---

## 🛠 Cara Menjalankan di VS Code

Agar kamu bisa menyusun dan melihat hasil PDF dari LaTeX di VS Code:

### 1. 📦 Requirement

Pastikan sistem kamu memiliki:

- [Visual Studio Code](https://code.visualstudio.com/)
- Extension: **LaTeX Workshop** (oleh James Yu)
- Distribusi LaTeX:
  - [TeX Live](https://www.tug.org/texlive/) (Linux/macOS)
  - [MiKTeX](https://miktex.org/download) (Windows)

### 2. 📂 Struktur Folder

Pastikan struktur project seperti ini:

```
.
├── naskah.tex           # File utama (entry point)
├── cover.tex
├── bab1.tex
├── bab2.tex
├── pembimbing.tex
├── penguji.tex
├── pengantar.tex
├── daftarpustaka.tex (opsional)
├── pustaka.bib          # File referensi BibTeX
├── gambar/              # Folder untuk gambar (jika ada)
```

### 3. ▶️ Compile

- Buka folder ini di VS Code
- Buka `naskah.tex`
- Tekan `Ctrl + Alt + B` (compile via LaTeX Workshop)
- Hasil PDF akan muncul otomatis di panel kanan

---

## 📚 Fitur LaTeX yang Digunakan

- `\input{}` untuk menyusun file per bab
- `bibtex` untuk daftar pustaka otomatis
- Penomoran halaman Romawi dan Arab
- `fancyhdr`, `geometry`, `titlesec` untuk pengaturan margin & header
- `enumitem`, `graphicx`, dll. untuk daftar dan gambar

---

## 🤝 Kontribusi

Proyek ini terbuka untuk kontribusi siapa saja.  
Kamu bisa bantu:

- Menyederhanakan template
- Menambahkan fitur atau gaya baru
- Mengubah jadi template resmi

---

## 📄 Lisensi

Dokumen ini dilisensikan dengan **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
Anda bebas:

- Membagikan — menyalin dan menyebarkan ulang materi
- Menyesuaikan — remix, mengubah, dan membangun dari materi

Asalkan Anda memberikan atribusi kepada:  
**I Wayan Pio Pratama**  
[Lisensi Resmi](https://creativecommons.org/licenses/by/4.0/)

> Konten ini bersifat dummy dan hanya untuk edukasi.

---

Selamat belajar LaTeX! ✍️
