# Laporan Kerja Praktek - SITARIS (Sistem Informasi Inventaris)

Repositori ini berisi dokumen LaTeX laporan kerja praktek untuk proyek mini SITARIS, yaitu sistem informasi inventaris untuk pencatatan barang, pengecekan stok, dan pembuatan laporan inventaris bagi perusahaan atau organisasi. Laporan ini disusun dalam konteks mata kuliah semester 5 menggunakan template LaTeX laporan kerja praktek Program Studi Sistem Informasi UIN Sultan Syarif Kasim Riau.

## Struktur Repositori

- `kerjapraktek.tex` - berkas utama yang menggabungkan seluruh komponen laporan
- `halamandepan/` - lembar pengesahan, kata pengantar, abstrak bahasa Indonesia, dan abstract bahasa Inggris
- `konten/` - isi laporan per bab
- `halamanbelakang/` - bagian penutup laporan
- `konfigurasi/` - pengaturan global dan data kerja praktek
- `kontrol/` - berkas kontrol template dan format dokumen
- `kerjapraktek.pdf` - hasil kompilasi akhir laporan yang ikut tersimpan di repositori

Berkas berakhiran `.aux`, `.bbl`, `.blg`, `.log`, `.toc`, `.lof`, `.lot`, `.out`, `.fls`, `.fdb_latexmk`, dan `.synctex.gz` adalah berkas antara yang dihasilkan selama proses kompilasi.

## Prasyarat

- Distribusi LaTeX, misalnya TeX Live, MiKTeX, atau MacTeX
- Editor LaTeX seperti TeXstudio atau Texmaker

## Cara Kompilasi

1. Clone repositori ini.
2. Kompilasi berkas utama:

   ```bash
   pdflatex kerjapraktek.tex
   bibtex kerjapraktek
   pdflatex kerjapraktek.tex
   pdflatex kerjapraktek.tex
   ```

   Alternatifnya gunakan `latexmk -pdf kerjapraktek.tex`.
3. Hasil akhir berupa berkas `kerjapraktek.pdf`. Untuk membaca laporannya saja, cukup buka berkas PDF tersebut tanpa perlu kompilasi.
