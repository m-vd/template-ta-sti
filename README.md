# Template LaTeX Tugas Akhir Prodi STI ITB

![Contoh](https://docs.google.com/uc?id=1B2VbiXJbae8E1xFx88CQbjTgse_WSzIs)

## Penjelasan Singkat

Template ini merupakan template laporan tugas akhir prodi STI ITB dalam LaTeX. Didalam template ini juga terdapat penjelasan dasar mengenai cara menggunakan LaTeX dan tata tulis karya ilmiah dalam Bahasa Indonesia. 

1. Struktur dokumen (pendahuluan, studi literatur, metodologi, hasil, penutup) menyesuaikan dengan struktur umum laporan tugas akhir. Bila ternyata kurang cocok, silakan ubah struktur tersebut agar sesuai dengan kebutuhan kalian. 
2. Penjelasan mengenai cara menggunakan LaTeX dibahas pada bab 2.
3. Penjelasan mengenai TTKI dan beberapa tips untuk isi laporan dibahas pada bab 3.
4. Penjelasan yang ditulis disini terbatas ke dasar saja, untuk lebih lengkapnya silahkan mencari sendiri lagi ya di internet atau referensi lainnya ;)
5. Sejauh ini, template baru diuji dan ditujukan untuk digunakan pada [Overleaf](https://overleaf.com).
6. Kalau ada yang salah atau kurang tepat tolong kabari supaya bisa diperbaiki ya.

## Konfigurasi Awal dan Struktur Template

1. Unduh repositori ini sebagai .zip.
2. Buka [Overleaf](https://overleaf.com)
3. Pilih New Project, kemudian Upload Project.
4. Unggah file .zip yang telah diunduh tadi
5. Buka file `master.tex` baris ke 11 dan ubah konfigurasi ini:

```
    \newcommand{\nim}{ *Isi NIM kalian disini* }
    \newcommand{\yearsidang}{ *Isi tahun sidang kalian disini* }
    \newcommand{\namapembimbing}{ *Isi nama pembimbing kalian disini* }
    \newcommand{\nippembimbing}{ *Isi NIP pembimbing kalian disini* }
    
    \begin{document}
    
        \title{ *Isi Judul TA kalian disini* }
        \date{ *Isi tanggal dan bulan sidang kalian disini* }
        \author{ *Isi nama kalian disini* }
``` 

Struktur template yang digunakan adalah seperti ini:
```
-- src
 |--- aset/              % simpan gambar atau aset lain disini  
 |--- config/            % konfigurasi, harusnya ga perlu diutak-atik kecuali ada kebutuhan khusus
 |--- komponen-akhir/    % lampiran
 |--- komponen-awal/     % cover, pengesahan, pernyataan, abstrak, prakata
   |--- cover.tex
   |--- pengesahan.tex
   |--- pernyataan.tex
   |--- abstrak-id.tex
   |--- abstrak-en.tex
   |--- prakata.tex
 |--- komponen-utama/    % bab 1-5
   |--- bab-1.tex
   |--- bab-2.tex
   |--- bab-3.tex
   |--- bab-4.tex
   |--- bab-5.tex
 |--- master.tex         % source code utama
 |--- references.bib     % database referensi yang diacu    

```


## Acknowledgement

1. Template ini merupakan modifikasi dari template yang disusun oleh [Petra Barus dan rekan](https://github.com/petrabarus/if-itb-latex) untuk prodi IF ITB.
2. Beberapa tata tulis yang dicantumkan berasal dari buku "Metode Penulisan Ilteks" oleh Tim Dosen TTKI ITB.
